a. How many data your publisher program will send to the message broker in one
run? 

- Program publisher mengirimkan 5 set informasi ke dalam sistem pengirim pesan pada satu waktu. Karena terdapat lima kali pemanggilan fungsi bernama publish_event.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?

- URL tersebut digunakan dalam kedua program subscriber dan publisher. Ini mengindikasikan bahwa kedua subscriber dan publisher terkoneksi ke server AMQP yang identik.


