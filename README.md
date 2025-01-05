# LAB-2.7

## 1. Instalar un linter 
En el entorno virtual, instalamos los linters:
![image](https://github.com/user-attachments/assets/9ae292f8-1206-4b68-b7d5-c0b30fe26133)

## 2. Ejecutar el linter

![image](https://github.com/user-attachments/assets/debc99de-79e9-4ef7-827f-04309a2627b6)


## 3. Instalar y Aplicar Coverage

![image](https://github.com/user-attachments/assets/ef8f587a-2ad5-4bb6-9dfd-4608117a8830)

Lo ejecutamos:
```
coverage run -m pytest
coverage report
coverage html  # Para generar un reporte en formato HTML
```
![image](https://github.com/user-attachments/assets/fa4a3b8b-74ab-44d1-9314-7779bb448e77)

![image](https://github.com/user-attachments/assets/21196234-751c-416d-bfe9-1f9d5c31e292)

![image](https://github.com/user-attachments/assets/99d1983a-e81a-4b60-86a1-b9c05c71cb45)

![image](https://github.com/user-attachments/assets/c3f42efc-8776-458c-9d51-5ee426109536)



![image](https://github.com/user-attachments/assets/41aaa00d-8172-4bcb-ba23-4d0ac55ec860)

Esto crea una carpeta htmlcov con un informe navegable en el archivo index.html.

## 4.  Instalar y Aplicar Trivy

```
sudo apt install wget -y
wget https://github.com/aquasecurity/trivy/releases/latest/download/trivy_Linux-64bit.deb
sudo dpkg -i trivy_Linux-64bit.deb
```
![image](https://github.com/user-attachments/assets/979b046a-10c6-4f5a-96f5-6ea9901346d5)

![image](https://github.com/user-attachments/assets/4a17f56d-bf25-44cf-88b4-cf06be7ed5d3)

![image](https://github.com/user-attachments/assets/34ac46f0-2dd3-4374-b76d-3854950b6172)

