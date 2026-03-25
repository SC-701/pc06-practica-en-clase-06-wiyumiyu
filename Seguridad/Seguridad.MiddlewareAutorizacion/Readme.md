# =========================================
#  Autorizacion.Middleware
# =========================================
# Middleware de ASP.NET Core 8 que consulta
# los roles del usuario autenticado y los
# agrega como Claims al HttpContext.User
# =========================================


## Paso 1 - Configurar GitHub Packages (solo 1 vez por máquina) (•‿•)

# Crea un PAT en tu cuenta de GitHub con scope:
#  read:packages

# Luego ejecuta:

dotnet nuget add source https://nuget.pkg.github.com/SC-701/index.json \
  --name github \
  --username Mariana \
  --password TU_PERSONAL_ACCESS_TOKEN \
  --store-password-in-clear-text


# Notas importantes (ง •̀_•́)ง
# - Reemplaza TU_PERSONAL_ACCESS_TOKEN por tu token real
# - "Mariana" es tu usuario (puedes cambiarlo si usas otro en GitHub)
# - Este comando se ejecuta una sola vez por máquina