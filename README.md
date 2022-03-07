### Moving the Cursor in Command Mode  

#### Single Movement  

**+**  
pindah kursor ke awal baris line selanjutnya  

**-**
pindah kursor ke awal baris line sebelumnya.  

#### Movement by Text Block

**w**  
Pindah kursor ke satu kata selanjutnya  

**W**  
Pindah ke satu Kata selanjutnya (kata yang dipisahkan oleh spasi)  

**b**  
Pindah ke satu kata sebelumnya  

**B**  
Pindah ke satu kata sebelumnya  

**<number>G**  
Untuk pindah menuju line ke-<number>.  

### Simple Edits  

#### Chaging Text  

**cw**  
mengubah kata  

**c2b**  
mengubah dua kata sebelumnya  

**c$**  
mengubah hingga akhir line  

**c0**  
mengubah hingga awal line  

#### Lines  

**cc**  
untuk mengubah satu line  

**C**
mengubah satu line yang terletak setelah kursor.  

#### Characters  

**r**  
mengganti (replace) satu karakter, tetapi tetap dalam mode normal (tidak masuk ke dalam mode insert). Dengan cara mengarahkan kursor ke karakter yang ingin diganti, kemudian inputkan
karakter yang dimaksudkan.  

#### Subtituting Text  

**s**  
mensubtitusi karakter (masuk ke mode insert).  

**S** === **cc**  
mensubtitusi satu line.  

**R**  
mengganti teks, masuk kedalam mode replace.  

#### Changing Case  

**~**  
mengubah sebuah karakter menjadi huruf besar atau huruf kecil.  

#### Deketing Text  

**dw**  
menghapus kata  

**dd**  
menghapus satu line.  

**D**  
menghapus satu line yang terletak pada setelah kursor.  

#### Moving Text  

**p**  
membuat line baru dibawah kursor, dan meletakkan paste di line baru tersebut.  

**P**  
membuat line baru pada kursor, dan meletakkan paste pada line baru tersebut.  

**xp**  
untuk memindahkan satu karakter, ke tempat lain setelah kursor berada.  

#### Copying Text  

**yy** || **Y**  
mengcopy satu baris.  

**y$**  

**y0**  

**yw**  

#### Repeating and Undoing Youf Last Command  

##### REPEAT  

**.**  
mengulangi command sebelumnya.  

##### UNDO  

**u**  

**U**  
mengundo hanya pada line tersebut, tidak dapat dilakukan jika sudah melakukan tindakan lainnya. 

**<c-r>**  
redo

### More Ways to Insert Text  

**A**  
insert teks pada akhir baris.  

**I**  
insert text pada awal kalimat di baris tersebut.  

**o**  
insert teks dibawah kursor.  

**O**  
insert teks diatas kursor.  

**s**  

**S**  

**R**  

#### Numeric Arguments for Insert Commands  

**<number>i<characters><Esc>**  
menginsertkan <character> sebanyak <number> pada sebuah line.  

**<number>r<characters><Esc>**  

**<number>S**  
menghapus sebanyak <number> line.  

### Joining Two Lines with J  

**J**
menggabung line dibawahnya menjadi satu line.  

**<number>J**
menggabung sebanyak <number> dibawahnya menjadi satu line.  

**J.**  
menggabung line dibawahnya satu per satu.  


