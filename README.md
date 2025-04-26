# 📦 GitHub Repository Initialization

Bu adımlarla yeni bir GitHub repository'si oluşturup ilk commit'i yapabilirsiniz.

---

## 🔹 Adım 1: README.md Oluştur

```bash
echo "# Ansible.Public" >> README.md

🔹 Adım 2: Git Reposunu Başlat
git init

🔹 Adım 3: Dosyaları Ekle ve Commit Yap
git add README.md
git commit -m "first commit"

🔹 Adım 4: Ana Branch'i Oluştur
git branch -M main

🔹 Adım 5: GitHub Remote Ekle
git remote add origin https://github.com/halukyilmaz55/Ansible.Public.git

🔹 Adım 6: Push Et (Yükle)
git push -u origin main

⚡ Alternatif Kısa Yol (Tekrar Remote ve Push)
git remote add origin https://github.com/halukyilmaz55/Ansible.Public.git
git branch -M main
git push -u origin main