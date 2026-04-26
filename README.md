# 🔀 sentinel-event-mesh (Legacy: sentinel-broker)

**Domain:** Infrastructure as Code (IaC) & Messaging Topology
**Rol:** Sinir Sistemi Konfigürasyonu

Bu repo bir Rust veya C++ yazılımı **içermez**. NATS JetStream'in çalışması için gereken mimari tanımları (Terraform, Ansible, Shell Script) barındırır. NATS'taki kanalların (Streams) boyutları, hangi verinin bellekte ne kadar kalacağı (Retention Policy) ve veri düşme (Drop) kuralları burada tanımlanır.

- **Altyapı Hedefi:** NATS JetStream (In-Memory HFT Mode)