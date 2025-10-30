**Daftar Perintah Pada Docker**

### ⚙️ **Mengontrol Container**

```bash
docker ps
```
menampilkan daftar container yang sedang berjalan
```bash
docker ps -a
```
Melihat semua container (termasuk yang berhenti)
```bash
docker stop [container_id]
```
Menghentikan container
```bash
docker start [container_id]
```
Menjalankan container yang sudah pernah dibuat
```bash
docker restart [container_id]
```
Merestart container
```bash
docker rm [container_id]
```
Menghapus container
### ⚓ **Network & Volume**
```bash
docker network ls
```
Menampilkan daftar network Docker
```bash
docker network create [nama_network]
```
Membuat network baru
```bash
docker network connect [nama_network] [nama_kontainer]
```
Memasukkan kontainer ke dalam network
```bash
docker network inspect [nama_network]
```
Melihat isi network
```bash
docker ps
```

```bash
docker ps
```

```bash
docker ps
```

```bash
docker ps
```
