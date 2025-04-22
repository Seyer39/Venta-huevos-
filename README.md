# Diccionario de preguntas y respuestas
preguntas_respuestas = {
    "¿Cuál es la ley que regula el contrato de trabajo en Chile?": "El Código del Trabajo regula el contrato de trabajo en Chile.",
    "¿Qué es una notificación de protesto de cheque?": "Es un acto formal que certifica que un cheque no ha sido pagado en la fecha de presentación y se notifica al librador.",
    # Agrega más preguntas y respuestas aquí
}

# Función para hacer preguntas
def hacer_pregunta(pregunta):
    respuesta = preguntas_respuestas.get(pregunta, "Lo siento, no tengo una respuesta para esa pregunta.")
    return respuesta

# Ejemplo de uso
pregunta_usuario = "¿Cuál es la ley que regula el contrato de trabajo en Chile?"
print("Pregunta:", pregunta_usuario)
print("Respuesta:", hacer_pregunta(pregunta_usuario))