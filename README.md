  # RetailTech S.A. — Gestión de la Configuración

  Repositorio del caso integrador para el curso **Gestión de la Configuración**
  Universidad del Quindío (Uniquindío) · 2026

  ## Estructura del proyecto
  - `src/` — Aplicación Node.js de RetailTech
  - `terraform/` — Infraestructura AWS como código
  - `ansible/` — Configuración de servidores
  - `k8s/` — Manifiestos de Kubernetes
  - `.github/workflows/` — Pipelines CI/CD
  
  ## Docente
  Juan Camilo Rodríguez Restrepo · Uniquindío 2026
  EOF

  cat > .gitignore << 'EOF'
  node_modules/
  .env
  *.log
  .terraform/
  *.tfstate
  *.tfstate.backup
  .DS_Store
  EOF
  
  mkdir -p src terraform ansible k8s .github/workflows
  touch src/.gitkeep terraform/.gitkeep ansible/.gitkeep k8s/.gitkeep






