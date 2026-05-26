# Cómo usar el vault de ITD

**1. Descargá Obsidian**
Entrá a obsidian.md y descargalo. Es gratis y funciona en Mac, Windows y celular.

**2. Instalá Git**
Entrá a git-scm.com y descargalo. Es un requisito para el paso siguiente — sin Git no podés clonar ni actualizar el vault.

**3. Cloná el vault**
Abrí la terminal, navegá a la carpeta donde querés guardar el vault y ejecutá:
```
git clone https://github.com/gmoscacofino/ITD-Vault.git
```
Esto lo descarga una sola vez.

**4. Abrilo en Obsidian**
Abrí Obsidian → **Open folder as vault** → seleccioná la carpeta `ITD-Vault`. Listo, ya podés navegar todo.

**5. Por dónde empezar**
- Si querés repasar teoría → carpeta `01-Teoria`
- Si querés ver ejercicios resueltos → carpeta `03-Ejercicios/Resueltos-Catedra`
- Si querés ver parciales anteriores → carpeta `04-Parciales-Anteriores`
- Si estás a punto de rendir → abrí `00-Sistema/Cheat-Sheet-Parcial`

**6. Para actualizar cuando haya cambios**
Abrí la terminal dentro de la carpeta del vault y escribí:
```
git pull
```
En dos segundos tenés todo actualizado.

**7. Opcional — conectarlo con Claude**
Si querés usar Claude como asistente de la materia sobre este vault, descargá Claude Code desde claude.ai/code. Una vez instalado, abrí la terminal dentro de la carpeta `ITD-Vault` y escribí `claude`. Claude va a leer automáticamente toda la estructura del vault y vas a poder hacerle preguntas, pedir que resuelva ejercicios o que explique conceptos — siempre usando el material de la cátedra como base.
