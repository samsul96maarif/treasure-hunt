#Treasure Hunt

##Deksripsi
1. symbols:
   1. '#' represent an obstacle.
   2. . represent an clear path.
   3. x represent the player's starting position.
2. A treasure is hidden within one of the clear path points, and the user must find it.
3. From the starting position, the user must navigate in a specific order:
   1. Up/North A step(s), then
   2. Right/East B step(s), then
   3. Down/South C step(s).
4. The program must output a list of probable coordinate points where the treasure might be located.
5. Bonus points: display the grid with all the probable treasure locations marked with a $ symbol.

##Requirement
1. python3

##Tutorial
1. jalankan "python3 main.py"

##Note
1. Karena pada deskripsi task tidak ada navigasi untuk ke kiri, maka permainan ini dibuat dengan 2 mode:
   1. strict mode, yaitu lokasi rintangan fix sesuai deskripsi task, dan navigasi tidak bisa ke kiri
   2. non strict mode, yaitu lokasi rintangan akan dirandom, dan navigasi bisa ke semua arah
