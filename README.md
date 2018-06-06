# Trabajo-Textil-ICC
# Proyecto final de ICC sobre tiempo y costos de producción de una empresa textil.
#La materia prima es el hilo.
#Cada kg. de hilo para jersey produce 0.7 kgs. de tela.
#Hilo para pique produce 0.5 kg de tela/kg hilo
#para franela, 0.3 kg. de tela/kg hilo
#velocidades estan en kg/hora
#Variables de ingreso:
#Cantidad por tipo de tela y prenda
#peso por tipo de tela y prenda
#precio por unidad por tipo de tela y prenda
#cree una lista por cada tipo de tela con el peso (en Kg)
#crear listas:
#inicializar:inicializa las listas
#calculo_tiempos:calcula tiempo de produccion por tela y tipo de prenda
#calculo_materia_prima:calcula los requerimientos de materia prima por tipo de tela
#calculo_costos:calcula los requerimientos de materia prima(hilo) por kilo de tela
#Materia_prima=Kg_tela/rendimiento
#outputs deben ser:
#tiempo de producción por tipo de tela
#cantidad de materia prima en Kg de hilo
#ganancias esperadas dado que se venden:
#Jersey: Polo a 30 soles Camisa a 50 soles Cuello a 5 soles
#Pique: Polo a 60 soles Camisa a 75 soles Cuello a 10 soles
#Franela: Polo a 60 soles Camisa a 80 soles y Cuello a 15 soles
#Kg de hilo cuesta 10 soles
#Responder que prenda recomendara priorizar en la produccion
#observando los tiempos y ganancias
velocidad_tejido=1.00
velocidad_teñido=10.00
velocidad_acabado=20.00
velocidad_confeccion_jersey_polos=0.20
velocidad_confeccion_jersey_camisas=0.50
velocidad_confeccion_jersey_cuellos=0.05
velocidad_confeccion_pique_polos=0.22
velocidad_confeccion_pique_camisas=0.33
velocidad_confeccion_pique_cuellos=0.04
velocidad_confeccion_franela_polos=0.25
velocidad_confeccion_franela_camisas=0.50
velocidad_confeccion_franela_cuellos=0.05
cantidad_jersey_polos=float(input("Cantidad de polos de jersey: "))
cantidad_jersey_camisas=float(input("Cantidad de camisas de jersey: "))
cantidad_jersey_cuellos=float(input("Cantidad de cuellos de jersey: "))
cantidad_pique_polos=float(input("Cantidad de polos pique: "))
cantidad_pique_camisas=float(input("Cantidad de camisas pique: "))
cantidad_pique_cuellos=float(input("Cantidad de cuellos de pique: "))
cantidad_franela_polos=float(input("Cantidad de polos de franela: "))
cantidad_franela_camisas=float(input("Cantidad de camisas de franela: "))
cantidad_franela_cuellos=float(input("Cantidad de cuellos de franela: "))
peso_jersey_polos=float(input("Peso de polos de jersey: "))
peso_jersey_camisas=float(input("Peso de camisas de jersey: "))
peso_jersey_cuellos=float(input("Peso de cuellos de jersey: "))
peso_pique_polos=float(input("Peso de polos pique: "))
peso_pique_camisas=float(input("Peso de camisas pique: "))
peso_pique_cuellos=float(input("Peso de cuellos de pique: "))
peso_franela_polos=float(input("Peso de polos de franela: "))
peso_franela_camisas=float(input("Peso de camisas de franela: "))
peso_franela_cuellos=float(input("Peso de cuellos de franela: "))
precio_jersey_polos=float(input("Precio por unidad de polos de jersey: "))
precio_jersey_camisas=float(input("Precio por unidad de camisas de jersey: "))
precio_jersey_cuellos=float(input("Precio por unidad de cuellos de jersey: "))
precio_pique_polos=float(input("Precio por unidad de polos pique: "))
precio_pique_camisas=float(input("Precio por unidad de camisas pique: "))
precio_pique_cuellos=float(input("Precio por unidad de cuellos de pique: "))
precio_franela_polos=float(input("Precio por unidad de polos de franela: "))
precio_franela_camisas=float(input("Precio por unidad de camisas de franela: "))
precio_franela_cuellos=float(input("Precio por unidad de cuellos de franela: "))
