# Responsive-Navbar
Responsive Navbar Yang Saya Pelajari dari Youtube Web Programming Unpas Yaitu Pak SandhikaGalih

Jika ingin Mengubah Animasi Arah Datangnya Navbar ketika Mode Mobile
Bisa dengan Cara Mengubah 

  nav ul {
    position: absolute;
    right: 0;
    top: 0;
    align-items: center;
    justify-content: space-evenly;
    z-index: -1;
    flex-direction: column;
    height: 100vh;
    width: 100%;
    background-color: rgba(127, 255, 212, 0.699);
    transform: translateY(-100%);
    transition: 1s;
  }
  
  Seperti di bawah ini
  Property Transform: translate(Y/X)
  Jika Memilih Y berarti Secara Vertical
  Jika Memilih X Berarti Secara Horizontal
