# ✈️ SkyReserve – Flight Booking System

SkyReserve adalah sistem pemesanan tiket pesawat online yang memungkinkan pengguna mencari, memesan, dan mengelola tiket penerbangan. Sistem dilengkapi **dashboard admin**, fitur **manajemen kursi**, dan **e-ticket otomatis**.

---

## 🚀 Fitur Utama

- 🔍 Pencarian penerbangan dengan filter lengkap  
- 👥 Sistem pemesanan multi-penumpang  
- 🛠️ Dashboard admin dengan CRUD lengkap  
- 💳 Simulasi pembayaran  
- 💺 Manajemen kursi pesawat  
- 🎫 Generate e-ticket otomatis  

---

## 📊 Progress Pengerjaan (7 Hari)

### ✅ Hari 1 – Setup & Database
- Initialize project repository  
- Setup database MySQL (15 tabel)  
- Konfigurasi environment variables  
- Setup authentication dasar  

### ✅ Hari 2 – Backend Core
- API endpoints untuk flights  
- API endpoints untuk airlines/airports  
- Flight search algorithm  
- Booking creation logic  

### ✅ Hari 3 – Frontend User
- Landing page design  
- Flight search interface  
- Flight results component  
- Responsive layout  

### ✅ Hari 4 – Admin Panel
- Admin dashboard layout  
- CRUD airlines  
- CRUD flights  
- Booking management  

### ✅ Hari 5 – Fitur Tambahan
- Payment gateway integration  
- Ticket generation  
- Email notifications  
- Booking history  

### ✅ Hari 6 – Testing & Polish
- Unit testing  
- Integration testing  
- Bug fixing  
- Performance optimization  

### ✅ Hari 7 – Deployment
- Production deployment  
- Database migration  
- Final testing  
- Documentation  

---

## 🛠️ Tech Stack

### **Frontend**
- Next.js 14 (App Router)  
- React 18 + TypeScript  
- Tailwind CSS + DaisyUI  
- Shadcn/UI  
- React Hook Form  
- Zod (validation)  
- Date-fns (date utilities)

### **Backend**
- Next.js API Routes  
- Prisma ORM  
- MySQL  
- NextAuth.js  
- Midtrans / Xendit (sandbox)  

### **Development & Deployment**
- Git & GitHub  
- Vercel (frontend deployment)  
- Railway (backend & database)  
- Postman (API testing)  
- ESLint & Prettier  

---

## 👥 Pembagian Tugas (3 Orang)

### 👨‍💻 **Orang 1 – Frontend Specialist**
**Tanggung Jawab:**
- Setup Next.js + Tailwind  
- Implementasi UI/UX design  
- Halaman user-facing:  
  - Landing page  
  - Flight search & results  
  - Booking flow  
  - User dashboard  
- Responsive design  
- Integrasi dengan API  

**Teknologi Fokus:** React, Tailwind, TypeScript, Shadcn/UI  

---

### 👩‍💻 **Orang 2 – Backend Specialist**
**Tanggung Jawab:**
- Database design & migration  
- Prisma schema & relations  
- API development (RESTful)  
- Authentication system  
- Flight search algorithm  
- Booking logic  
- Payment integration  
- Data validation & error handling  

**Teknologi Fokus:** Next.js API, Prisma, MySQL, NextAuth  

---

### 👨‍💻 **Orang 3 – Full-Stack & DevOps**
**Tanggung Jawab:**
- Project configuration & setup  
- Admin panel development  
- CRUD operations  
- Analytics components  
- Frontend–Backend integration  
- Testing (unit, integration, E2E)  
- Deployment & CI/CD:  
  - Vercel  
  - Railway  
- Environment configuration  
- Monitoring setup  

**Teknologi Fokus:** TypeScript, Testing, Deployment, Integration  

---

## 📄 Lisensi
This project is licensed under the MIT License.

---

# 🧑‍💻 GitHub Collaboration Commands

Berikut adalah command dasar Git & GitHub yang paling sering dipakai dalam kerja kelompok.

---

## 📥 1. Clone Repository (ambil project pertama kali)
git clone https://github.com/username/nama-repo.git

##🔀 2. Cek Status Perubahan
git status

##➕ 3. Add File ke Staging
###Add semua file:
git add .
Add file tertentu:
git add nama_file.ext

##💬 4. Commit Perubahan
git commit -m "pesan commit"

##⬆️ 5. Push ke GitHub (upload perubahan)
git push
###Kalau pertama kali push branch baru:
git push -u origin nama-branch

##⬇️ 6. Pull Perubahan dari Teman (wajib sebelum mulai kerja)
git pull

###Pull branch tertentu:
git pull origin nama-branch

##🌿 7. Membuat Branch Baru
git checkout -b nama-branch-baru

##🔄 8. Pindah Branch
git checkout nama-branch

##🔀 9. Merge Branch (biasanya dilakukan oleh lead atau saat membuat PR)
###Masuk ke branch tujuan, misal main:
git checkout main
git merge nama-branch

##🗑️ 10. Hapus Branch
###Hapus branch lokal:
git branch -d nama-branch

###Hapus branch di GitHub:
git push origin --delete nama-branch

##🧹 11. Reset File ke Versi Terakhir
###Reset 1 file:
git checkout -- nama_file.ext

###Reset semua file yang belum di-commit:
git reset --hard

##🧩 12. Stash Perubahan (kalau mau pindah branch tapi belum commit)
git stash

###Balikin lagi:
git stash pop

##🛠️ 13. Konfigurasi Git (pertama kali install)
git config --global user.name "Nama Kamu"
git config --global user.email "emailkamu@example.com"
