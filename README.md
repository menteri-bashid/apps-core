# BashID Core Files

## Requirements
- Hugo (https://gohugo.io/)
- NPM (https://www.npmjs.com/)

## Installation
```
$ npm install
```

## How it works
```
$ bashid-builder.sh
```

## Contributing Guidelines
Bagi kamu yang ingin berkontribusi konten maupun tema, kamu dapat mengikuti langkah-langkah dibawah ini :smile:

### First Step
- Fork it

### Contribute Content
- Jalankan ``bashid-builder.sh`` dan ikuti petunjuk untuk membuat konten baru
- Setelah berhasil, maka terdapat direktori lokasi file konten
- Kamu dapat mengedit konten dengan format markdown
- Untuk preview konten yang telah kamu buat, kamu dapat menjalankan ``bashid-builder.sh`` dan masuk mode staging
- Jika dirasa konten sudah pas, kamu dapat langsung menggunakan mode production dan melakukan ``pull request``

### Contribute Themes
Read pls https://gohugo.io/getting-started/directory-structure/ 

- CSS Location
	- External ``layout/partials/css.html``
	- Internal ``static/styles/*.scss`` (Automatic compiling SASS with gulp look at gulpfile.js)