# Scripts de Configuración de Clúster Kubernetes

Este repositorio contiene los Bash Scripts necesarios para configurar un clúster de Kubernetes en su versión v1.27, ideal para la automatización y gestión de aplicaciones en contenedores.

## Scripts

1. `setup_containerd.sh`: Configura Containerd con ajustes de kernel y red para Kubernetes en cada servidor.
2. `install_kubernetes.sh`: Prepara el sistema para Kubernetes, instala los componentes esenciales y previene actualizaciones automáticas en cada servidor.
3. `init_cluster.sh`: Inicia el clúster de Kubernetes, configura `kubectl`, instala Calico y verifica el estado de los nodos.

## Uso

Sigue estos pasos en el Plano de Control:
1. Ejecuta `setup_containerd.sh`.
2. Ejecuta `install_kubernetes.sh`.
3. Ejecuta `init_cluster.sh`.

## Prerrequisitos

- **Sistema Operativo**: Linux.
- **Conocimientos**: Administración de sistemas Linux y contenedores.
- **Herramientas**: `curl`, `sudo`, terminal.
- **Red**: Conexión a internet.
- **Permisos**: Privilegios de superusuario o `sudo`.
- **Hardware**: Al menos dos servidores, uno para el Control Plane y otro como Worker Node.

## Notas Adicionales

- **Kubernetes**: Orquestador de contenedores para la administración de aplicaciones.
- **Containerd**: Plataforma de ejecución de contenedores.

Consulta los comentarios en cada script para más detalles.

