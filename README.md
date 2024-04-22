# Hola

> An awesome project.

```flow
start=>start: Inicio
config=>operation: Configurar datos de entrada (CENTERLINEID, PK_INI, PK_FIN, EvaluacionID)
execute=>operation: Ejecutar el script
generate=>operation: Generar cartas de alineación
save=>operation: Exportar PDF
end=>end: Fin

start->config->execute->generate->save->end
```
