# 🤝 **Contributing to Richkeyrick Portfolio**

Terima kasih atas minat Anda untuk berkontribusi pada proyek ini! Dokumen ini berisi guidelines untuk kontribusi.

---

## 📋 **Table of Contents**

- [🎯 Ways to Contribute](#ways-to-contribute)
- [🐛 Bug Reports](#bug-reports)
- [💡 Feature Suggestions](#feature-suggestions)
- [🌐 Translations](#translations)
- [📝 Documentation](#documentation)
- [⚖️ Code of Conduct](#code-of-conduct)
- [📞 Contact](#contact)

---

## 🎯 **Ways to Contribute**

### **1. 🐛 Bug Reports**
Jika Anda menemukan bug atau issue:
- Pastikan belum dilaporkan di [Issues](../../issues)
- Gunakan template bug report
- Sertakan langkah reproduksi yang jelas
- Lampirkan screenshot jika relevan
- Informasikan browser/device yang digunakan

### **2. 💡 Feature Suggestions**
Punya ide untuk fitur baru?
- Buat [Feature Request](../../issues/new?template=feature_request.md)
- Jelaskan use case dan benefit
- Sertakan mockup/wireframe jika ada
- Diskusikan dengan community terlebih dahulu

### **3. 🌐 Translations**
Bantu kami menjangkau audiens global:
- Terjemahkan konten ke bahasa baru
- Review terjemahan yang ada
- Perbaiki kesalahan terjemahan
- Pastikan konteks tetap terjaga

### **4. 📝 Documentation**
Perbaiki atau tambahkan dokumentasi:
- README updates
- Komentar kode
- Tutorial/guide baru
- FAQ expansion

### **5. ⭐ Social Support**
- Star repository ini
- Share di social media
- Berikan testimonial
- Refer ke teman/rekan

---

## 🐛 **Bug Reports**

### **Template Bug Report**

```markdown
## 🐛 Bug Description
Deskripsi singkat bug yang ditemukan.

## 🔄 Steps to Reproduce
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

## ✅ Expected Behavior
Apa yang seharusnya terjadi?

## ❌ Actual Behavior
Apa yang sebenarnya terjadi?

## 📸 Screenshots
Jika ada, lampirkan screenshot.

## 💻 Environment
- **OS:** [e.g., Windows 11, macOS 14, Android 14]
- **Browser:** [e.g., Chrome 120, Safari 17]
- **Device:** [e.g., Desktop, iPhone 15, Samsung S24]
- **Screen Resolution:** [e.g., 1920x1080]

## 📝 Additional Context
Informasi tambahan yang relevan.
```

### **Priority Labels**

| Label | Description | Response Time |
|-------|-------------|---------------|
| `🔴 critical` | Site down, security issue | < 24 hours |
| `🟠 high` | Major feature broken | < 3 days |
| `🟡 medium` | Minor bug, workaround exists | < 1 week |
| `🟢 low` | Cosmetic, enhancement | < 2 weeks |

---

## 💡 **Feature Suggestions**

### **Template Feature Request**

```markdown
## 💡 Feature Summary
Deskripsi singkat fitur yang diinginkan.

## 🎯 Motivation
Kenapa fitur ini penting? Problem apa yang diselesaikan?

## 📋 Proposed Solution
Bagaimana fitur ini seharusnya bekerja?

## 🔄 Alternatives Considered
Alternatif lain yang sudah dipertimbangkan?

## 📸 Mockups/Screenshots
Jika ada, lampirkan desain/mockup.

## 📝 Additional Context
Informasi tambahan yang relevan.
```

### **Feature Categories**

| Category | Description | Example |
|----------|-------------|---------|
| `✨ enhancement` | New feature | AI chat improvement |
| `🎨 design` | UI/UX changes | New animation |
| `⚡ performance` | Speed optimization | Lazy loading |
| `♿ accessibility` | A11y improvements | Screen reader |
| `🌍 i18n` | Internationalization | New language |
| `🔒 security` | Security features | CSP update |

---

## 🌐 **Translations**

### **Supported Languages**

Currently supported:
- 🇮🇩 **Bahasa Indonesia** (ID) - Base language
- 🇬🇧 **English** (EN) - Complete

### **Adding New Language**

1. **Check if translation needed**
   - Lihat [Issues](../../issues) dengan label `🌍 i18n`
   - Pastikan belum ada PR untuk bahasa tersebut

2. **Translation Process**
   ```
   1. Fork repository
   2. Create branch: feature/translation-[language-code]
   3. Copy translations.js structure
   4. Translate all keys
   5. Test locally
   6. Submit PR
   ```

3. **Translation Guidelines**
   - ✅ Gunakan bahasa formal untuk konten profesional
   - ✅ Pertahankan konteks teknis
   - ✅ Localize date/time formats
   - ✅ Consider RTL languages (Arabic, Hebrew)
   - ❌ Jangan gunakan Google Translate mentah
   - ❌ Jangan ubah struktur kode/teknis

### **Translation File Structure**

```javascript
// js/data/translations-[lang].js
export const translations = {
  meta: {
    title: "Richkeyrick Portfolio",
    description: "..."
  },
  sections: {
    hero: {
      title: "...",
      subtitle: "..."
    }
    // ... more sections
  }
};
```

### **Review Process**

Translations akan direview oleh:
1. **Native speakers** (jika tersedia)
2. **Maintainer** untuk konsistensi
3. **Community** untuk feedback

---

## 📝 **Documentation**

### **Types of Documentation**

| Type | Location | Audience |
|------|----------|----------|
| **README** | `/README.md` | General visitors |
| **Features** | `/FEATURES.md` | Technical recruiters |
| **Roadmap** | `/ROADMAP.md` | Stakeholders |
| **Contributing** | `/CONTRIBUTING.md` | Contributors |
| **Security** | `/SECURITY.md` | Security researchers |
| **Code Comments** | In source files | Developers |

### **Documentation Standards**

- ✅ Gunakan Bahasa Indonesia atau English
- ✅ Gunakan Markdown formatting
- ✅ Include code examples
- ✅ Add screenshots where helpful
- ✅ Keep updated with changes
- ✅ Link to related docs

---

## ⚖️ **Code of Conduct**

### **Our Pledge**

Kami berkomitmen untuk membuat environment yang:
- 🏳️‍🌈 **Welcoming** - Ramah untuk semua background
- 🤝 **Respectful** - Hormat dalam diskusi
- 💡 **Constructive** - Feedback yang membangun
- 🎯 **Professional** - Fokus pada tujuan

### **Expected Behavior**

✅ **Do:**
- Gunakan bahasa yang sopan dan profesional
- Terima constructive criticism gracefully
- Fokus pada apa yang terbaik untuk community
- Tunjukkan empathy kepada members lain
- Respect berbagai viewpoints dan experiences

❌ **Don't:**
- Gunakan sexualized language atau imagery
- Troll, insult/derogatory comments, personal attacks
- Public atau private harassment
- Publish private information tanpa permission
- Other conduct yang tidak etis/unprofessional

### **Enforcement**

Pelanggaran dapat mengakibatkan:
1. ⚠️ **Warning** - First offense
2. 🚫 **Temporary Ban** - Repeated violations
3. ⛔ **Permanent Ban** - Severe violations

Laporkan pelanggaran ke: info@richkeyrick.com

---

## 🏷️ **Issue Labels**

| Label | Color | Description |
|-------|-------|-------------|
| `🐛 bug` | 🔴 Red | Something isn't working |
| `✨ enhancement` | 🟣 Purple | New feature request |
| `📚 documentation` | 🔵 Blue | Improvements to docs |
| `🌍 i18n` | 🟢 Green | Translation/internationalization |
| `🎨 design` | 🟡 Yellow | UI/UX related |
| `⚡ performance` | 🟠 Orange | Speed optimization |
| `♿ accessibility` | 🔵 Light Blue | A11y improvements |
| `🔒 security` | ⚫ Black | Security issues |
| `❓ question` | ⚪ Gray | Questions from users |
| `🔄 duplicate` | ⚪ Gray | Duplicate of existing issue |
| `❌ wontfix` | ⚪ Gray | Won't be addressed |
| `✅ resolved` | 🟢 Green | Issue resolved |

---

## 🚀 **Quick Start for Contributors**

### **1. Fork & Clone**

```bash
# Fork repository di GitHub, lalu clone:
git clone https://github.com/[your-username]/richkeyrick-portfolio.git
cd richkeyrick-portfolio
```

### **2. Setup Development**

```bash
# Install dependencies (jika ada)
npm install

# Start local server
python -m http.server 8000
# atau
npx serve .
```

### **3. Create Branch**

```bash
git checkout -b feature/your-feature-name
# atau
git checkout -b fix/bug-description
```

### **4. Make Changes**

- Edit files sesuai kebutuhan
- Test perubahan di browser
- Pastikan tidak ada console errors

### **5. Commit & Push**

```bash
git add .
git commit -m "feat: add [description]"
git push origin feature/your-feature-name
```

### **6. Create Pull Request**

- Go to GitHub repository
- Click "Compare & pull request"
- Fill PR template
- Submit untuk review

---

## 📝 **Commit Message Guidelines**

Format: `<type>: <description>`

### **Types**

| Type | Description |
|------|-------------|
| `feat` | New feature |
| `fix` | Bug fix |
| `docs` | Documentation changes |
| `style` | CSS/styling changes |
| `refactor` | Code restructuring |
| `perf` | Performance improvements |
| `test` | Adding/updating tests |
| `chore` | Maintenance tasks |

### **Examples**

```
✅ feat: add AI chat typing indicator
✅ fix: resolve mobile menu overflow
✅ docs: update README with new features
✅ style: improve dark mode contrast
✅ perf: lazy load portfolio images
```

---

## ✅ **Checklist Before Submitting**

### **For Bug Reports:**
- [ ] Issue belum dilaporkan sebelumnya
- [ ] Sertakan langkah reproduksi
- [ ] Sertakan environment details
- [ ] Sertakan screenshot jika relevan

### **For Feature Requests:**
- [ ] Jelaskan problem yang diselesaikan
- [ ] Sertakan use case
- [ ] Pertimbangkan alternative solutions
- [ ] Jelaskan benefit untuk users

### **For Pull Requests:**
- [ ] Code berfungsi dengan baik
- [ ] Tidak ada console errors
- [ ] Responsive di mobile
- [ ] Accessibility checked
- [ ] Documentation updated
- [ ] Commit messages jelas

---

## 🎁 **Recognition**

Contributors akan diakui di:
- 📜 README.md Contributors section
- 🏆 Hall of Fame page (planned)
- 🎉 Release notes
- 📧 Newsletter mention (with permission)

---

## 📞 **Contact**

Untuk pertanyaan tentang contributing:

- 📧 **Email:** info@richkeyrick.com
- 💬 **WhatsApp:** +62 852 6011 3313
- 🐛 **Issues:** [GitHub Issues](../../issues)

---

## 🙏 **Thank You!**

Setiap kontribusi, sekecil apapun, sangat dihargai. Together we build something amazing!

**- Richkeyrick Team**

---

*Last Updated: April 2026*
