### Movement by Screen  

#### Scrolling the screen

**<c-F>**  
gulir maju satu layar  

**<c-B>**  
gulir mundur satu layar  

**<c-D>**  
gulir maju setengah layar  

**<c-U>**  
gulir mundur setengah layar  

#### Repositioning the screen with z  

**z<cr>** || **z+**  
memindahkan posisi line saat ini ke paling atas layar dan gulir  

**z.**  
memindahkan posisi line saat ini ke tengah layar dan gulir  

**z-**  
memindahkan posisi line saat ini ke paling bawah layar dan gulir  

**<number>z<cr>**  
memindahkan line ke-<number> ke paling atas layar dan gulir  

### Movement by Text Blocks  

**e**  
pindah ke akhir kata pada current kursor.  

**E**  
pindah ke akhir kata (kata yang dipisahkan spasi).  

**(**  
pindah ke awal pada kalimat saat ini.  

**)**  
pindah ke awal pada kalimat selanjutnya.  

**{**  
pindah ke awal pada paragraf saat ini.  

**}**  
pindah ke awal pada paragraf selanjutnya.  

[[  
pindah ke awal pada section saat ini.  

]]  
pindah ke akhir pada section selanjutnya.  

### Movement by Search  

#### Reapeating Searches  

**n**  
Repeat pencarian ke arah yang searah.  

**N**  
repeat pencarian ke arah yang berlawanan.  

**/**  
repeat pencariah ke arah maju.  

**?**  
repeat pencarian ke arah mundur.  

#### Current Line Searches 

**f<character>**..
menemukan kemunculan <character> selanjutnya pada line.  

**F<character>**  
menemukan kemunculan <character> sebelumnya pada line.  

**t<character>**  
menemukan (memindahkan kursor) ke karakter selanjutnya kemudian meletakkan kursor pada satu <character> sebelumnya di line.  

**T<character>**  
menemukan (memindahkan kursor) ke satu karakter sebelumnya kemudian meletakkan kursor pada satu <character> setelahnya di line.

**;**  
repeat find command sebelumnya ke arah yang searah.  

**,**  
repeat find command sebelumnya ke arah yang berlawanan.  

### Movement by Line number  

#### The G (Go To) Command

**<c-G>**  
menampilkan current line (bukan command untuk menggerakkan).  

**<number>G**  
pindak ke line <number>.  

**G**  
pindah ke akhir baris pada file.  

**``**  
kembali ke letak kursor sebelumnya dimana letak sebelum mengedit.  

**''**  
kembali ke letak kursor sebelumnya (meletakkan kursor di awal line) dimana letak sebelum mengedit.  

