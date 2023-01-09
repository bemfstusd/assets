# Assets WebHook
repository ini digunakan untuk reverse-api ke website resmi [BEM-FST USD](https://usd.ac.id/bemfst)

disini hanya berisikan data.json yang nantinya akan ditampilkan di halaman utama.
`visi` : string
`misi` : array of string
`komite` : array of object 
`komite[][url]` : hanya berisikan url sebuah gambar, bisa menggunakan aplikasi upload apa saja semacam `imgbb`. tidak disarankan untuk menggunakan `encoded:base64`
`kontak` : object yang berisikan hanya email dan instagram. 
