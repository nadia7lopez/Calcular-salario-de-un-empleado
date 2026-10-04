	def salario_neto_empleado():
	    
	    # Entrada de datos: Solicitar al usuario el salario bruto y el porcentaje de impuestos y deducciones adicionales
	    salarioBruto = float(input("Ingrese salario bruto: "))
	    porcentajeImpuestos = float(input("Ingrese porcentaje de impuestos: "))
	    deduccionesAdicionales = float(input("Ingrese deducciones adicionales: "))
	
	    # Proceso: Calcular el salario neto con fórmula
	    impuesto = round(salarioBruto * (porcentajeImpuestos / 100), 2)
	    salarioNeto = round(salarioBruto - impuesto - deduccionesAdicionales, 2)
	
	    # Salidas: Mostrar salario neto, impuestos y deducciones adicionales
	    print(f"Salario neto del empleado: {salarioNeto}")
	    print(f"Impuestos: {impuesto}")
	    print(f"Deducciones adicionales: {deduccionesAdicionales}")
	
	if __name__ == "__main__":
	    salario_neto_empleado()
