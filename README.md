<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gülnisa Oğuz - Kişisel Web Sayfası</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        nav {
            margin-top: 0.5rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.1rem;
        }
        section {
            padding: 2rem 0;
        }
        .about, .blog, .contact, .recommendations {
            background: #fff;
            padding: 2rem;
            margin: 1rem 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .about h2, .blog h2, .contact h2, .recommendations h2 {
            margin-top: 0;
            font-size: 1.5rem;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
        footer p {
            margin: 0;
        }
        .highlight {
            background: #f9f9f9;
            padding: 2rem;
            border-radius: 5px;
            margin: 1rem 0;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .recommendations ul {
            list-style: none;
            padding: 0;
        }
        .recommendations ul li {
            padding: 0.5rem 0;
        }
        .search-container {
            margin: 1rem 0;
        }
        .search-container input[type="text"] {
            width: 100%;
            padding: 0.5rem;
            font-size: 1rem;
        }
    </style>
    <script>
        function searchRecommendations() {
            const searchTerm = document.getElementById('search').value.toLowerCase();
            const items = document.querySelectorAll('.recommendations ul li');
            
            items.forEach(item => {
                const text = item.textContent.toLowerCase();
                if (text.includes(searchTerm)) {
                    item.style.display = '';
                } else {
                    item.style.display = 'none';
                }
            });
        }
    </script>
</head>
<body>
    <header>
        <div class="container">
            <h1>Gülnisa Oğuz</h1>
            <nav>
                <a href="#highlight">Son Teknolojik Gelişmeler</a>
                <a href="#about">Hakkında</a>
                <a href="#blog">Blog</a>
                <a href="#recommendations">Öneriler</a>
                <a href="#contact">İletişim</a>
            </nav>
        </div>
    </header>
    <div class="container">
        <section id="highlight" class="highlight">
            <h2>Son Teknolojik Gelişmeler</h2>
            <p>Teknoloji dünyası her geçen gün daha hızlı bir şekilde gelişiyor ve değişiyor. İşte son dönemde dikkat çeken bazı teknolojik gelişmeler:</p>
            <h3>1. Yapay Zeka ve Makine Öğrenimi</h3>
            <p>Yapay zeka (YZ) ve makine öğrenimi, günümüzün en önemli teknoloji trendlerinden biri olmaya devam ediyor. Özellikle dil işleme, görüntü tanıma ve otomasyon alanlarında yapılan yenilikler, birçok endüstride devrim yaratıyor. OpenAI'nin ChatGPT gibi modelleri, kullanıcılarla daha doğal ve etkili bir etkileşim sağlıyor.</p>
            <h3>2. Kuantum Bilgisayarlar</h3>
            <p>Kuantum bilgisayarlar, hesaplama gücünde çığır açan bir yenilik olarak öne çıkıyor. Bu yeni nesil bilgisayarlar, klasik bilgisayarlardan çok daha karmaşık problemleri hızlı bir şekilde çözme potansiyeline sahip. IBM ve Google gibi teknoloji devleri, kuantum bilgisayarları daha erişilebilir hale getirmek için çalışmalarını sürdürüyor.</p>
            <h3>3. 5G Teknolojisi</h3>
            <p>5G teknolojisi, mobil ağların hızını ve kapasitesini önemli ölçüde artırarak daha hızlı internet bağlantıları ve daha düşük gecikme süreleri sağlıyor. Bu teknoloji, özellikle akıllı şehirler, IoT (Nesnelerin İnterneti) ve artırılmış gerçeklik (AR) uygulamalarında büyük bir etki yaratacak.</p>
            <h3>4. Metaverse ve Sanal Gerçeklik</h3>
            <p>Metaverse ve sanal gerçeklik (VR) teknolojileri, sanal dünyalarda etkileşimde bulunmayı daha gerçekçi hale getiriyor. Facebook'un Meta olarak yeniden markalaşması, bu alandaki yenilikleri ve fırsatları gösteriyor. VR gözlükleri ve platformları, oyunlardan eğitim uygulamalarına kadar geniş bir kullanım yelpazesi sunuyor.</p>
            <p>Bu teknolojiler, gelecekte yaşam biçimimizi ve iş yapma şeklimizi büyük ölçüde değiştirebilir. Teknolojik gelişmeleri takip etmek, bu değişimlere uyum sağlamak için önemli bir adım olacaktır.</p>
        </section>
        <section id="about" class="about">
            <h2>Hakkında</h2>
            <p>Merhaba! Ben Gülnisa Oğuz, bir yazılım geliştirici ve teknoloji meraklısıyım. Yıllardır teknoloji ve yazılım dünyasında çalışıyorum ve çeşitli projelerle deneyim kazandım.</p>
            <p>Üzerinde çalıştığım projeler ve yazılım geliştirme süreçleri hakkında daha fazla bilgiye bu sayfada ulaşabilirsiniz.</p>
        </section>
        <section id="blog" class="blog">
            <h2>Blog</h2>
            <article>
                <h3>Yapay Zeka ve Günümüz İş Dünyası</h3>
                <p>Yapay zeka (YZ) teknolojisi, iş dünyasında devrim yaratıyor. Özellikle otomasyon, veri analizi ve müşteri hizmetleri gibi alanlarda YZ'nin etkisi giderek artıyor. Şirketler, bu teknolojiyi kullanarak verimliliklerini artırıyor ve maliyetlerini düşürüyor. Yapay zeka uygulamalarının gelecekte iş süreçlerini nasıl daha da dönüştüreceğini merakla bekliyoruz.</p>
            </article>
            <article>
                <h3>Metaverse ve Sosyal Etkileşimler</h3>
                <p>Metaverse, sanal dünyalarda etkileşimde bulunma şeklimizi değiştiriyor. İnsanlar artık sadece sosyal medya üzerinden değil, sanal gerçeklik ortamlarında da etkileşimde bulunuyor. Bu yeni platformlar, sosyal etkileşimlerimizi nasıl yeniden şekillendirecek ve hayatımıza nasıl yeni dinamikler katacak, önümüzdeki yıllarda daha iyi anlaşılacak.</p>
            </article>
            <article>
                <h3>Kuantum Bilgisayarların Geleceği</h3>
                <p>Kuantum bilgisayarlar, klasik bilgisayarlardan çok daha güçlü işlem kapasitelerine sahip. Bu teknolojinin gelişimi, özellikle karmaşık hesaplamalar ve büyük veri analizleri konusunda devrim yaratabilir. Kuantum bilgisayarların önündeki zorluklar ve bu alandaki ilerlemeler, teknoloji dünyasında büyük bir ilgi ile takip ediliyor.</p>
            </article>
        </section>
        <section id="recommendations" class="recommendations">
            <h2>Önerdiğim Kitaplar ve Filmler</h2>
            <div class="search-container">
                <input type="text" id="search" placeholder="Arama yapın..." onkeyup="searchRecommendations()">
            </div>
            <h3>Kitaplar</h3>
            <ul>
                <li>**"The Last Devil to Die"** - **Richard Osman**</li>
                <li>**"Fourth Wing"** - **Rebecca Yarros**</li>
                <li>**"Happy Place"** - **Emily Henry**</li>
                <li>**"The Wishing Game"** - **Meg Shaffer**</li>
                <li>**"Malibu Rising"** - **Taylor Jenkins Reid**</li>
            </ul>
            <h3>Filmler</h3>
            <ul>
                <li>**"Oppenheimer"** - **Christopher Nolan**</li>
                <li>**"Barbie"** - **Greta Gerwig**</li>
                <li>**"Killers of the Flower Moon"** - **Martin Scorsese**</li>
                <li>**"Dune: Part Two"** - **Denis Villeneuve**</li>
                <li>**"The Marvels"** - **Nia DaCosta**</li>
            </ul>
        </section>
        <section id="contact" class="contact">
            <h2>İletişim</h2>
            <p>Bana e-posta yoluyla ulaşabilirsiniz: <a href="mailto:info@gunisaoguz.com">info@gunisaoguz.com</a></p>
        </section>
    </div>
    <footer>
        <p>© 2024 Gülnisa Oğuz. Tüm Hakları Saklıdır.</p>
    </footer>
</body>
</html>

