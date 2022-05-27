# Workflow
Nama : Dwi Nur Ellisa

NIM  : E41200115

Repository ini ditujukan untuk memenuhi tugas dari matakuliah Literasi Digital

# Clone Reepository Workflow
Pertama saya membuat sebuah repository dengan nama Workflow pada github. Setelah itu, saya melakukan clonning repository menggunakan gitbash dengan perintah: ```git clone https://github.com/dwinurellisa/Workflow.git``` Dilanjutkan dengan masuk pada direktori workflow dengan perintah: ```cd workflow```

Selanjutnya saya menambahkan sebuah file dengan nama PerkalianMatriks.html . Selanjutnya saya akan memindahkan file PerkalianMatriks.html yang berada pada working area menuju staging area dengan perintah: ```git add``` . untuk memindahkan lebih dari satu (semua) file. Setelah berhasil, commit file tersebut dengan perintah: ```git commit -m "Menambahkan file PerkalianMatriks.html"``` , Dilanjutkan dengan perintah: ```git push```

Kemudian saya menambahkan file baru dengan nama ImplementasiBootstrap.html menggunakan perintah: ```git add ImplementasiBootstrap.html```. Setelah berhasil, commit file tersebut dengan perintah: ```git commit -m "Menambahkan file ImplementasiBootstrap.html"``` , Dilanjutkan dengan perintah: ```git push```

Menambahkan sebuah folder js dengan perintah: ```git add js```. Setelah berhasil, commit folder dengan perintah: ```git commit -m "Menambahkan folder js"``` , Dilanjutkan dengan perintah: ```git push```

# Membuat Branch dan Melakukan Merge
Saya akan menambahkan sebuah branch(cabang) dengan nama tampilan menggunakan perintah: ```git checkout -b tampilan``` .Kini head pada repo ini berpindah dari main menuju tampilan dan dapat dilihat pada tulisan berwarna biru disebelah kanan. Selanjutnya saya membuat sebuah folder yang bernama css pada branch tampilan. Lalu ketikkan perintah: ```git add .``` dilanjutkan dengan perintah: ```git commit -m "Menambahkan folder style.css"``` dilanjutkan dengan perintah: ```git push --set-upstream origin tampilan```

Menambahkan folder lagi yaitu img dengan perintah: ```git add img``` dilanjutkan dengan perintah: ```git commit -m "Menambahkan img"``` dilanjutkan dengan perintah: ```git push```

Selanjutnya saya ingin menggabungkan folder css yang ada pada branch tampilan menuju branch main. Pertama berpindah terlebih dahulu ke branch main dengan perintah: ```git checkout main``` dilanjutkan dengan menggabungkan folder css dengan perintah: ```git merge tampilan``` ,dan ```git push``` maka penggabungan branch berhasil.
