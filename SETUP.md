# 🚀 Setup GitHub Actions

## ⚡ Langkah Setup (PENTING!)

### 1️⃣ Enable Workflow Permissions

Ke: **Settings → Actions → General → Workflow permissions**

✅ Pilih: **Read and write permissions**  
✅ Centang: **Allow GitHub Actions to create and approve pull requests**  
✅ Save

---

### 2️⃣ Setup METRICS_TOKEN (Optional)

Jika mau pakai Metrics workflow:

1. Buat Personal Access Token:
   - **Settings → Developer settings → Personal access tokens → Tokens (classic)**
   - Generate new token (classic)
   - Name: `METRICS_TOKEN`
   - Select scopes: `public_repo`
   - Generate & copy token

2. Add ke Repository Secrets:
   - **Repository Settings → Secrets and variables → Actions**
   - New repository secret
   - Name: `METRICS_TOKEN`
   - Value: [paste token]
   - Add secret

---

### 3️⃣ Run Workflows

Go to: **Actions tab**

1. **Generate Snake** → Run workflow
2. **Metrics** → Run workflow (jika sudah setup token)

---

### 4️⃣ Update Social Links (Optional)

Edit `README.md` di section `[NETWORK.SCAN]`:

```markdown
└── 📧 Email: your.email@example.com

Social Networks Detected:
├── 💼 LinkedIn: linkedin.com/in/yourprofile
├── 📷 Instagram: @yourusername
└── 💬 Discord: YourName#1234
```

---

## ✅ Checklist

- [x] Push ke GitHub ✓
- [x] Buat branch output ✓
- [ ] Enable workflow permissions
- [ ] Setup METRICS_TOKEN (optional)
- [ ] Run workflows manual
- [ ] Update social links
- [ ] Pin 6 repository terbaik

---

## 🎨 Customization

### Ganti Warna
Search & replace `00ff88` dengan:
- `00d4ff` (Neon Blue)
- `a855f7` (Neon Purple)
- `ff0080` (Neon Pink)

### Update Project Links
Di section `[PROJECTS.DB]`, ganti `[→](#)` dengan URL repo:
```markdown
| 📱 **Absen App** | ... | `🟢 In Dev` | [View](https://github.com/raytrifeno/absen-app) |
```

---

**Done! Profile siap digunakan! 🔥**
