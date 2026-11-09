# tfg-Gantt


gantt
    title Cronograma del TFG - Sistema de Gestión de Biblioteca
    dateFormat YYYY-MM-DD
    axisFormat %d/%m
    excludes weekends

    section Planificación
    Análisis de requisitos          :a1, 2026-11-09, 3d
    Diseño de casos de uso          :a2, after a1, 2d
    Diseño de la base de datos      :a3, after a2, 3d

    section Base de datos
    Creación de tablas en MySQL     :b1, after a3, 3d
    Inserción de datos de prueba   :b2, after b1, 2d

    section Desarrollo
    Diseño de la interfaz          :c1, after b2, 3d
    Gestión de usuarios             :c2, after c1, 3d
    Gestión de libros               :c3, after c2, 4d
    Gestión de préstamos y devoluciones :c4, after c3, 4d
    Búsqueda y disponibilidad       :c5, after c4, 3d

    section Integración y pruebas
    Conexión e integración          :d1, after c5, 2d
    Pruebas de funcionamiento       :d2, after d1, 3d
    Corrección de errores           :d3, after d2, 2d

    section Finalización
    Elaboración de documentación    :e1, after d3, 4d
    Revisión final del proyecto     :e2, after e1, 2d
    Preparación de la presentación  :e3, after e2, 2d
