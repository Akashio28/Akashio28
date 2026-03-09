<!-- Header dengan Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&color=00f5ff&center=true&vCenter=true&width=700&lines=Hi+👋+I'm+Acacio+Elezito;I+am+a+Software+Developer;Network+Enthusiast;Full-Stack+Developer;Open+Source+Lover;Network+Enthusiast)](https://git.io/typing-svg)


class MahasiswaInformatika:
    def __init__(self):
        self.nama = "Acacio Elezito"
        self.universitas = "Universitas Nasional Timor-Leste (UNTL)"
        self.lokasi = "Dili, Timor-Leste"
        self.program_studi = "Teknik Informatika"
        self.julukan = "El Sagarata"
        self.bidang_fokus = {
            "Jaringan Komputer": ["Konfigurasi Jaringan", "Pemeliharaan", "Troubleshooting"],
            "Kecerdasan Buatan": ["Dasar-dasar AI", "Fundamental Machine Learning"],
            "Pengembangan Software": ["Full-Stack Developer", "Open Source"],
            "Sistem Linux": ["Debian", "Konfigurasi Hyprland"]
        }
        self.stack_teknis = {
            "Bahasa": ["Python", "PHP"],
            "Tools": ["Anaconda", "Bootstrap", "Apache"],
            "Library": ["NumPy"]
        }
        self.studi_saat_ini = [
            "Konfigurasi dan troubleshooting jaringan",
            "Fundamental kecerdasan buatan",
            "Administrasi sistem Linux (Debian)",
            "Konfigurasi environment desktop Hyprland",
            "Pengembangan Full-Stack"
        ]
        self.keahlian_teknis = [
            "Dasar-dasar Jaringan",
            "Perawatan Komputer", 
            "Dukungan IT",
            "Linux (Debian)",
            "Konfigurasi Hyprland",
            "Python Programming",
            "PHP Development"
        ]

    def get_info_lengkap(self):
        return f"""
╔══════════════════════════════════════════╗
║  Hi 👋, I'm {self.nama} / {self.julukan}
║  {self.program_studi} at {self.universitas}
║  Based in {self.lokasi}
║  
║  🔭 I'm currently studying:
║  {chr(10).join(['  • ' + s for s in self.studi_saat_ini])}
║  
║  🌱 I'm interested in:
║  • Network Engineering
║  • Artificial Intelligence
║  • Full-Stack Development
║  • Open Source Contribution
╚══════════════════════════════════════════╝
        """

    def get_kontak(self):
        kontak = {
            "Facebook": "https://facebook.com/EL%20Sagarata",
            "Instagram": "https://instagram.com/elezitoac",
            "X (Twitter)": "https://x.com/acacioelezito04",
            "Email": "acacioelezito933@gmail.com"
        }
        return kontak

    def get_github_stats(self):
        return {
            "username": "Akashio28",
            "followers": "✨ Follow me on GitHub",
            "contribution_graph": "https://github-readme-activity-graph.vercel.app/graph?username=Akashio28&theme=react-dark&hide_border=true&area=true"
        }

# Inisialisasi profil
profil_saya = MahasiswaInformatika()

# Untuk menampilkan di README.md atau console
if __name__ == "__main__":
    print(profil_saya.get_info_lengkap())
    
    print("\n📊 Bidang Fokus:")
    for bidang, skills in profil_saya.bidang_fokus.items():
        print(f"  📌 {bidang}: {', '.join(skills)}")
    
    print("\n💻 Tech Stack:")
    for kategori, items in profil_saya.stack_teknis.items():
        print(f"  🔧 {kategori}: {', '.join(items)}")
    
    print("\n🌐 Connect with me:")
    for platform, link in profil_saya.get_kontak().items():
        print(f"  • {platform}: {link}")
    
    print(f"\n📊 GitHub: @{profil_saya.get_github_stats()['username']}")
<!-- Contribution Graph -->
## 📈 Contribution Graph
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Akashio28&theme=react-dark&hide_border=true&area=true" alt="Contribution Graph" width="100%"/>
  <img src="https://gh-heat.anishroy.com/api/Akashio28/svg?theme=blue&darkMode=true&palette=0,20,40,60,80,100" />
</div>

<!-- Connect with me -->
<div align="center">
  🌐 Connect with me

  [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)](https://facebook.com/EL%20Sagarata)
  [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/elezitoac)
  [![X](https://img.shields.io/badge/X-black.svg?style=for-the-badge&logo=X&logoColor=white)](https://x.com/acacioelezito04)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:acacioelezito933@gmail.com)
</div>

<!-- Tech Stack -->
<div align="center">
  ### 💻 Tech Stack
  
  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
  ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
  ![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
  ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
  ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)
  ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
</div>

<!-- Python Class Representation -->
```python
{profil_saya.get_info_lengkap()}
