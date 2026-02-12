# DIPERMI – Gestión de Usuarios en Linux

Herramienta desarrollada en Python para la administración de usuarios en sistemas Linux mediante una interfaz gráfica intuitiva. Proyecto realizado como Trabajo de Fin de Grado (ASIR).

## 📌 Descripción

DIPERMI es una aplicación orientada a la gestión segura y eficiente de usuarios en entornos Linux. Permite realizar tareas administrativas desde una interfaz gráfica desarrollada con Tkinter, ejecutando comandos del sistema mediante `subprocess` y registrando todas las acciones realizadas.

El proyecto está enfocado en demostrar competencias en administración de sistemas, automatización y control de permisos.

## ⚙️ Funcionalidades

- Creación de usuarios  
- Eliminación de usuarios  
- Modificación de cuentas  
- Gestión de grupos  
- Validación de contraseñas mediante expresiones regulares  
- Registro de eventos en `/var/log`  
- Interfaz gráfica intuitiva  
- Ejecución controlada de comandos del sistema  

## 🛠️ Tecnologías utilizadas

- Python 3  
- Tkinter  
- Subprocess  
- Logging  
- Expresiones regulares (Regex)  
- Linux (Debian/Ubuntu)  

## 📋 Requisitos

- Sistema operativo Linux  
- Python 3 instalado  
- Permisos de superusuario para ejecutar tareas administrativas  

## 🚀 Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/tuusuario/dipermi.git
```

2. Acceder al directorio:

```bash
cd dipermi
```

3. Ejecutar la aplicación:

```bash
sudo python3 DIPERMI.py
```

## 📂 Estructura del proyecto

```
DIPERMI/
│
├── DIPERMI.py
├── LICENSE
└── README.md
```

## 🎯 Objetivos del proyecto

- Aplicar conocimientos de administración de sistemas Linux.  
- Automatizar tareas de gestión de usuarios.  
- Implementar un sistema de registro de eventos.  
- Desarrollar una herramienta funcional con interfaz gráfica.  
- Documentar y estructurar un proyecto técnico completo.  

## 🔐 Seguridad

La aplicación ejecuta comandos del sistema, por lo que requiere permisos administrativos. Se recomienda utilizarla en entornos de pruebas o controlados.

## 👨‍💻 Autor

Rubén Hans Rodríguez  
Trabajo de Fin de Grado – Administración de Sistemas Informáticos en Red (ASIR)
