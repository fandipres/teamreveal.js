<p align="center">
  <img src="img/react_logo.png" alt="reveal.js" height="300">
  <br><br>
  <b><a href="https://reactjs.org/">reactjs.org</a></b>
</p>

<h1>Apa Itu React</h1>

## Berkenalan dengan React
<p>React merupakan salah satu library Javascript terpopuler untuk membuat user interface (UI). Tool ini menawarkan respons cepat untuk user input dengan menggunakan metode baru dalam proses rendering website.</p>
<p>React memungkinkan developer untuk membuat user interface yang kompleks dari kumpulan-kumpulan kode dengan cara memecah bagian-bagian dari UI tersebut menjadi "component" yang lebih kecil.</p>

## Siapa Pengembang React
<img src="https://thediffpodcast.com/assets/images/jordan-2c43ff762e625d49ea58424e3e74188a.jpg" height="250"/>
<p>Resmi dirilis pada tahun 2013, React JS dibuat oleh Jordan Walke yang merupakan salah satu karyawan Facebook (sekarang Meta). Sebagai kerangka kerja aplikasi open-source yang dibuat oleh Facebook, React juga dapat digunakan untuk mengembangkan aplikasi multiplatform.</p>

<h1>Kelebihan dan Kekurangan</h1>

## Kelebihan React
- Mudah untuk dipelajari dan dipergunakan karena menerapkan gaya penulisan deklaratif.
- Memungkinkan pengembangan aplikasi multiplatform, dengan demikian dalam satu pengembangan aplikasi dapat berjalan pada beberapa paltform.
- Penulisan komponen lebih mudah dengan adanya JSX yang dapat mengombinasikan HTML dan Javascript.
- Komponen yang bersifat reusability sehingga kode yang sebelum-sebelumnyanya dipergunakan tidak perlu mengalami banyak perubahan.
- Komunitas yang aktif dan cukup besar.

## Kekurangan React
- Dokumentasi yang tidak terlalu lengkap sehingga bagi para "pemula" akan cukup sulit untuk mempelajarinya.
- Kinerja yang cukup rendah sebagai dampak dari aplikasi yang dapat berjalan pada beberapa paltform.
- Masalah debugging dan kompabilitas.

<h1>Performansi</h1>
<p>Uji coba performansi dilakukan dengan membandingkan performa dari React dan Native DOM dalam hal meload 100 baris data. Informasi lebih lanjut mengenai uji coba performansi dapat dilihat melalui postingan Object Partners berikut <a href="https://objectpartners.com/2015/11/19/comparing-react-js-performance-vs-native-dom/">Comparing React.js performance vs. native DOM</a>.</p>

<h1>Contoh Kode</h1>

```
class HelloMessage extends React.Component {render() {
  return (
    <div>
      Hello {this.props.name}
    </div>
  );
}}
					  
ReactDOM.render(
  <HelloMessage name="World" />,
  document.getElementById('hello-example')
);
 ```
