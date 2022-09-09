# WS_JKN

point :
kuota pasien di jadwal dokter di tambah untuk kuota pasien bpjs
Pasien BPJS mengunakan kode jenis bayar = BPJ
pasien onsite wajib membuat SEP dari khanza dan data pasien seperti noka dan nik harus sesuai
untuk folder api-bpjsfktl/conf.php karna mengunakan nginx maka ada tambahan di line 391 sampai 404. silahkan di hapus jika mengunakan apache.

KhanzaHMSServiceMobileJKNERM :
edit di frmUtama.java 
script masih bergabung Mjkn sama Bpjs Onsite
jika ingin berjalan sendiri sendiri, edit per case. silahkan hapus di case pasien JKN atau non jkn
lihat script yang sudah di sediakan di ws_....txt
edit lib di nbproject/project.properties. sesuaikan lokasi lib
NOTE : KARNA SERING EDIT LANGSUNG BUILD JADI SCRIPTNYA LANGSUNG DI HAPUS, JADI LUPA ADA PERUBAHAN ATAU TIDAK :V . PAKAI YANG LANGSUNG JAR YANG SUDAH DI TES BERHASIL.