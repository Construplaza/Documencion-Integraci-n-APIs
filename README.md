# Template para nuestros sistemas

- En readme debe incluir descripcion del repositorio.
- El código debe estar completamente comentado.
- La documentación debe ir adjunta en un link dentro del ReadMe que lo enviará a la carpeta privada de Google Drive. <a href='https://drive.google.com/drive/folders/1HRDTUFhQcwbHng-tzRFeIYVCR2veAcGc?usp=drive_link'>Link Acá (Debe solicitar permiso la primera vez)</a>
- Se deberá incluir al final del ReadMe la bitacora de cambios de la documentación que debe ir como el siguiente ejemplo: 2024-06-12 - Patrick Ocampo - Se incluye el paso a paso para realizar las acciones del nuevo módulo - página 10 - Comentario si es necesario.

# Reglas

- El main branch se llamada Main

# Branchesx

- El branch debe ser llamado por el nombre del módulo que esta desarrollando y el numero de tiquete que jira.
- El branch debe ser eliminado cuando el desarrollo es concluido.

Ejemplo: [Compras]-[FAC 81]

# Commits

- Los commits deben ser bien descriptivos y tienen la siguiente nomenclatura: Tipo de Acción, Módulo en desarrollo, el número de tiquete en jira y la descripción

Ejemplo: [FIX] [Compras] [FAC 81] [Descripción]

# Merges

- Se debe solicitar el merge a Luis Segura, Jose Moreno y Patrick Ocampo, en caso de que alguno de estos sea el solitante debe pedirlo a alguno de los otros dos.

# Tipo de Acción

[ADD] for adding new modules;

[FIX] for bug fixes: mostly used in stable version but also valid if you are fixing a recent bug in development version;

[REF] for refactoring: when a feature is heavily rewritten;

[IMP] for improvements: most of the changes done in development version are incremental improvements not related to another tag;

[REM] for removing resources: removing dead code, removing views, removing modules, …;

[REV] for reverting commits: if a commit causes issues or is not wanted reverting it is done using this tag;

[MOV] for moving files: use git move and do not change content of moved file otherwise Git may loose track and history of the file; also used when moving code from one file to another;

[REL] for release commits: new major or minor stable versions;

# Bitacora de Documentación

- Incluir aquí la bitacora
