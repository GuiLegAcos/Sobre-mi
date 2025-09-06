# 0) (solo una vez) Configura tu identidad de git
git config --global user.name "Tu Nombre"
git config --global user.email "tu-email@loquesea.com"

# 1) Clona tu repo de perfil
git clone https://github.com/TU_USUARIO/TU_USUARIO.git
cd TU_USUARIO

# 2) Abre y pega el README
nano README.md     # pega el contenido, Ctrl+O, Enter para guardar, Ctrl+X para salir

# 3) Sube cambios
git add README.md
git commit -m "feat: presentación full stack"
git push origin main
