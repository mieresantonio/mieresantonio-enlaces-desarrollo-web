# 🚀 Recursos de Desarrollo Full Stack

Este repositorio es una recopilación organizada de enlaces, documentación, ejemplos de código y herramientas útiles proporcionadas en las clases del Profesor Yolfrank. Está diseñado para servir como guía de referencia rápida y apoyo durante los estudios.

---

## 🌐 Módulo 1: Fundamentos Web (HTML y CSS)
- [HTML Introduction (W3Schools - Inglés)](https://www.w3schools.com/html/html_intro.asp)
- [CSS Introduction (W3Schools - Inglés)](https://www.w3schools.com/css/css_intro.asp)
- [Introducción a HTML5 (LenguajeHTML - Español)](https://lenguajehtml.com/html/)
- [Introducción a CSS (LenguajeCSS - Español)](https://lenguajecss.com/css/)

---

## 🎨 Módulo 2: Formularios, Flexbox y Bootstrap
- [Documentación Oficial de Bootstrap](https://getbootstrap.com)
- [Formularios en Bootstrap](https://getbootstrap.com/docs/5.3/forms/overview/)
- [Guía de Flexbox (MDN Mozilla)](https://developer.mozilla.org/es/docs/Learn_web_development/Core/CSS_layout/Flexbox)
- 🎮 [Juego: Flexbox Froggy](https://flexboxfroggy.com/#es)
- 🎮 [Juego: Flexbox Defense](http://www.flexboxdefense.com/)

---

## 💻 Módulo 3: Línea de Comandos (CLI)
- [Command Line Reference (SS64)](https://ss64.com)
- [Manual Pages (LinuxCommand)](https://linuxcommand.org/lc3_man_page_index.php)
- 🎮 [Command Challenge](https://cmdchallenge.com)

---

## 🟨 Módulo 4: JavaScript y el DOM

### Conceptos Básicos
- [Tutorial JavaScript (W3Schools)](https://www.w3schools.com/js/default.asp)
- [Aprende JavaScript en Y minutos](https://learnxinyminutes.com/es/javascript/)
- [JavaScript.info (Español)](https://es.javascript.info/)

### Arrays y Bucles
- [Métodos de Arrays (W3Schools)](https://www.w3schools.com/JS/js_array_methods.asp)
- [Iteración de Arrays (W3Schools)](https://www.w3schools.com/JS/js_array_iteration.asp)
- [Bucle `for...in` (W3Schools)](https://www.w3schools.com/js/js_loop_forin.asp)
- [Bucle `for...of` (W3Schools)](https://www.w3schools.com/js/js_loop_forof.asp)
- [Referencia `for...of` (W3Schools)](https://www.w3schools.com/jsref/jsref_forof.asp)

### DOM, Eventos y Event Bubbling
- [Eventos en JavaScript (W3Schools)](https://www.w3schools.com/JS/js_events.asp)
- [Objeto Event (W3Schools)](https://www.w3schools.com/jsref/dom_obj_event.asp)
- [Métodos del DOM (W3Schools)](https://www.w3schools.com/js/js_htmldom_methods.asp)
- [Referencia Oficial del DOM (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model) *(Usar como consulta, no lectura obligatoria).*

> **🎯 Objetivos clave del DOM:**
> * Entender qué es el DOM y seleccionar elementos (`querySelector`, `querySelectorAll`).
> * Escuchar eventos usando `addEventListener()`.
> * Utilizar el objeto event (`event.target`, `event.type`).
> * Manipular elementos (`innerText`, `innerHTML`, `getAttribute()`, `setAttribute()`).
> * Comprender cómo funciona *Event Bubbling* e identificar cuándo usar `stopPropagation()` y `preventDefault()`.

---

## 🧪 Módulo 5: Testing con Jest
- [Using Matchers (Documentación Oficial)](https://jestjs.io/docs/using-matchers)
- [Expect (Documentación Oficial)](https://jestjs.io/docs/expect)

**Ejemplos de matchers frecuentes:**
```javascript
expect(2 + 2).toBe(4);

expect({ nombre: "Ana" }).toEqual({ nombre: "Ana" });

expect("Hola").toBeTruthy();
expect("").toBeFalsy();

expect(["JS", "Node", "Jest"]).toContain("Jest");

expect("Hola Mundo").toMatch(/Mundo/);

expect(10).toBeGreaterThan(5);
expect(3).toBeLessThan(5);

expect(null).toBeNull();
expect(undefined).toBeUndefined();
```
---

## **⚛️ Módulo 6: React**

### **Introducción y Conceptos Clave**
- [React Learn](https://react.dev/learn)
- [Your First Component](https://react.dev/learn/your-first-component)
- [Thinking in React](https://react.dev/learn/thinking-in-react)
- [React Tutorial (W3Schools)](https://www.w3schools.com/react/)

> **💡 Conceptos Fundamentales:**
> * React es una librería para construir interfaces basadas en **componentes**.
> * La información se recibe mediante **props** y se almacena en el **state**.
> * `import` y `export` permiten organizar el código en múltiples archivos.

### **Estado (State) y Hooks**
- [State: A Component's Memory](https://react.dev/learn/state-a-components-memory) (y [en español](https://es.react.dev/learn/state-a-components-memory))
- [Gestión del estado](https://es.react.dev/learn/managing-state)
- [useState (Docs Oficiales)](https://es.react.dev/reference/react/useState)
- [Hooks de React](https://es.react.dev/reference/react/hooks)

> *Nota: Cuando el estado (state) cambia mediante `useState`, React vuelve a renderizar el componente automáticamente.*

### **Colección de Gists (React y JS)**
- [`useState` en React](https://gist.github.com/devAbreu/a8c41fb1b2b23f88a333907b16454c54)
- [`useEffect` en React](https://gist.github.com/devAbreu/055fa7787b75e22862124ea51e92641c)
- [`fetch` y `async/await`](https://gist.github.com/devAbreu/12f77b471536d1aeddd7ea763befa399)
- [Props y PropTypes](https://gist.github.com/devAbreu/222c71b4d4b78cbac4c8a66983251fd6)
- [`.map()` y su uso en React](https://gist.github.com/devAbreu/57aa1baa9deb4af7c846968baf9445eb)
- [Desestructuración en JS](https://gist.github.com/devAbreu/fe3ff65e028b0f882b10589b7cd78828)
- [Spread Operator (...)](https://gist.github.com/devAbreu/9e034d7770c7f952e050b3f5bc55b829)

### **React Router y Context API**
- [Rutas en React con react-router-dom](https://gist.github.com/devAbreu/1010cfc7b16a162980f7b1b3bfe9bfd1)
- [React Flux: Gestión de Estado con useReducer y useContext](https://gist.github.com/devAbreu/f177f53e71a2bde9b419c36c589e3702)
- 👨‍💻 [Repositorio de ejemplo práctico (Context API)](https://github.com/4GeeksAcademy/devAbreu-context-api-react)

---

## **🐍 Módulo 7: Introducción a Python**
- [Tutorial de Python (W3Schools)](https://www.w3schools.com/python/)
- [Learn X in Y Minutes (Python)](https://learnxinyminutes.com/es/python/)
- [Documentación oficial de Python](https://docs.python.org/3/tutorial/)
- [Python Tutor (Visualizador de ejecución paso a paso)](https://pythontutor.com/python-compiler.html)
- [El Libro de Python](https://ellibrodepython.com)

---

## **🗄️ Módulo 8: Bases de Datos (SQL y SQLAlchemy)**

### **SQL Puro**
- [W3Schools SQL (referencia y ejemplos)](https://www.w3schools.com/sql/)
- [TutorialsPoint SQL (sintaxis y conceptos)](https://www.tutorialspoint.com/sql/sql-syntax.htm)
- [SQLBolt (ejercicios interactivos paso a paso)](https://sqlbolt.com/)
- 🛠️ [SQLite Online (laboratorio de pruebas en el navegador)](https://sqliteonline.com/)

> **⚠️ Recomendación:** No se limiten a leer la teoría. Escriban las consultas, modifíquenlas, provoquen errores y entiendan por qué ocurren. La mejor forma de aprender SQL es practicando.

### **Modelado de Datos (SQLAlchemy)**
- [SQLAlchemy 2.0+ con Flask-SQLAlchemy](https://gist.github.com/devAbreu/1776c3ba40add454728140a1de74a034)
- [Resumen de Relaciones y SQLAlchemy 2.x](https://gist.github.com/devAbreu/edb2eb20f4fcc6845000ad0513e2231a)
- [Guía de Consultas SQLAlchemy 2.0+ y API REST](https://gist.github.com/devAbreu/25b0232838f631cd2f3984f260f5a531)

**Ejemplo Práctico: Relaciones 1:1, 1:N y N:M con Flask-SQLAlchemy**
```python
from flask_sqlalchemy import SQLAlchemy
from sqlalchemy import Column, ForeignKey, String, Table
from sqlalchemy.orm import Mapped, mapped_column, relationship

db = SQLAlchemy()

# Tabla de asociación (Muchos a Muchos)
student_course = Table("student_course", db.metadata,
                       Column("student_id", ForeignKey("student.id")),
                       Column("course_id", ForeignKey("course.id"))
                       )

class Student(db.Model):
    __tablename__ = "student"
    id: Mapped[int] = mapped_column(primary_key=True)
    name: Mapped[str] = mapped_column(String(100))
    email: Mapped[str] = mapped_column(String(120), unique=True)

    card: Mapped["StudentCard"] = relationship(back_populates="student")
    courses: Mapped[list["Course"]] = relationship(
        secondary=student_course, back_populates="students")

class StudentCard(db.Model):
    __tablename__ = "student_card"
    id: Mapped[int] = mapped_column(primary_key=True)
    card_number: Mapped[str] = mapped_column(String(30))
    issue_date: Mapped[str] = mapped_column(String(20))
    student_id: Mapped[int] = mapped_column(ForeignKey("student.id"))

    student: Mapped["Student"] = relationship(back_populates="card")

class Teacher(db.Model):
    __tablename__ = "teacher"
    id: Mapped[int] = mapped_column(primary_key=True)
    name: Mapped[str] = mapped_column(String(100))
    courses: Mapped[list["Course"]] = relationship(back_populates="teacher")

class Course(db.Model):
    __tablename__ = "course"
    id: Mapped[int] = mapped_column(primary_key=True)
    title: Mapped[str] = mapped_column(String(100))
    teacher_id: Mapped[int] = mapped_column(ForeignKey("teacher.id"))

    teacher: Mapped["Teacher"] = relationship(back_populates="courses")
    students: Mapped[list["Student"]] = relationship(
        secondary=student_course, back_populates="courses")
```
---

🤝 Cómo contribuir
Si tienes un enlace útil, siéntete libre de abrir un Pull Request o dejar un Issue para agregarlo a la lista.
