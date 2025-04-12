# Crear el diagrama de casos de uso
dot = Digraph(comment='Diagrama de Casos de Uso - Gestión de Eventos')

# Definir los actores
dot.node('O', 'Organizador', shape='actor')
dot.node('A', 'Asistente', shape='actor')
dot.node('ADM', 'Administrador', shape='actor')

# Definir los casos de uso
use_cases = {
    'CU1': 'Crear evento',
    'CU2': 'Editar evento',
    'CU3': 'Inscribirse a evento',
    'CU4': 'Enviar confirmación',
    'CU5': 'Ver lista de inscritos',
    'CU6': 'Generar reportes'}

for code, label in use_cases.items():
    dot.node(code, label, shape='ellipse')

# Conectar actores con casos de uso
dot.edges([
    ('O', 'CU1'),
    ('O', 'CU2'),
    ('O', 'CU5'),
    ('A', 'CU3'),
    ('A', 'CU4'),
    ('ADM', 'CU6')])# Guardar como imagen
dot.format = 'png'
dot.render('diagrama_casos_uso_eventos', cleanup=True)
