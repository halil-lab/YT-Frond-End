<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kişisel Web Sitesi</title>
    <link rel="stylesheet" href="/css/style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Muhammed Halil Çalı</h1>
            <nav>
                <ul>
                    <li><a href="#about">Hakkımda</a></li>
                    <li><a href="#portfolio">Portföy</a></li>
                    <li><a href="#contact">İletişim</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="about">
        <div class="container">
            <h2>Hakkımda</h2>
            <p>Takım çalışmasına yatkın olduğumu düşünüyorum. Çalışmalar sırasında çeşitli fikirler üretebilir,takım arkadaşlarımla çalışmakta olduğumuz proje üzerine kreatif çalışmalar yapabilirim. İş demek her an bir kriz oluşabileceği anlamına gelir,kriz yönetiminde de başarılı olduğumu düşünüyorum. Soğukkanlı bir şekilde krizi çözmeye yönelik alternatif rotalar oluşturabilir ve sorunun çözülmesine hatrı sayılır katkıda bulunabilirim böylece projemiz sorunsuz ilerlemez ancak doğabilecek her sorunu akılcı çözümle ortadan kaldırabileceğimizin garantisini verecek bir takımla yola çıkar ve hedefimize ulaşırız.</p>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Faaliyet Alanları</h2>
            <!-- Portföy öğelerini buraya ekle -->
            Yıldız Teknik Üniversitesi Harita Mühendisliği Programı Öğrencsi <br>
            Atatürk Üniversitesi Bilgisayar Programcılığı Öğrencisi <br>
            YTÜ Jeoenformatik Kulübü Yönetim Kurulu Üyesi <br>
            YTÜ Sosyal Sorumluluk Kulübü Çorbada Tuzun Olsun Projesi Koordinatörü <br>
            YTÜ TEDx Topluluğu Organizasyon Ekibi Üyesi <br>
            Kızılay Gönüllüsü <br>
            Tema Vakfı Göüllüsü <br>
            TOG Vakfı Bursiyeri ve Gönüllüsü <br>
            23 Vakfı Üyesi <br>
            YTÜ SKYLAB Kulübü Aktif Üyesi <br>
            YTÜ SPARK Kulübü Aktif Üyesi <br>
            Tubitak 2209-b sanayi <br>
            Tubitak 1001 Yapay Zeka ile tarımsal bitkilerin drone görüntüleri ile izlenmesi <br>
            Jeodezik deprem ölçümleri saha ekibi üyesi

        </div>
        <body>
          </div>
            <h1>Diller</h1>
            <table>
                <thead>
                    <th>Dil Adı</th>
                    <th>Seviye</th>
                    <th>Öğrenildiği Yer</th>
                </thead>
                <tbody>
                    <tr>
                        <td>İngilizce</td>
                        <td>B1</td>
                        <td>YTÜ Hazırlık</td>
                    </tr>
                    <tr>
                        <td>Almanca</td>
                        <td>Temel</td>
                        <td>Kişisel Uğraş</td>
                    </tr>
                </tbody>
            </table>
          </div>
        </body>
    </section>

    <section id="contact">
        <div class="container">
            <h2>İletişim</h2>
            <!-- İletişim formunu buraya ekle -->
            Numara: 0552 624 04 16 <br>
            e-posta: muhammedhalilcali@gmail.com <br>
            Adres: ...
        </div>
    </section>


</body>
</html>

style
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}

header {
    background-color: #584747;
    color: antiquewhite;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 24px;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 50px 0;
}

section h2 {
    margin-top: 0;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1px 0;
}

body h1{
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}


table, tr, td, th{
    border: 1px solid black;
    border-collapse: collapse;
    text-align: center;
    padding: 1px 0;
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}


/* Responsive Tasarım */
@media (max-width: 768px) {
    .container {
        width: 90%;
    }

    header h1 {
        font-size: 20px;
    }

    nav ul li {
        margin-right: 10px;
    }

    section {
        padding: 30px 0;
    }
}

