

# REFLECTION

a. How many data your publisher program will send to the message broker in one
run? 

- Program publisher mengirimkan 5 set informasi ke dalam sistem pengirim pesan pada satu waktu. Karena terdapat lima kali pemanggilan fungsi bernama publish_event.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
program, what does it mean?

- URL tersebut digunakan dalam kedua program subscriber dan publisher. Ini mengindikasikan bahwa kedua subscriber dan publisher terkoneksi ke server AMQP yang identik.

#  Running RabbitMQ as message broker

<a href="https://ibb.co/rpJNmVp"><img src="https://i.ibb.co/NNzbsMN/Screenshot-2024-04-22-112451.png" alt="Screenshot-2024-04-22-112451" border="0"></a>


#  Sending and processing event

- Screenshot berhasilnya menerima 5 event message broker dari publisher pada terminal subscriber.
  <a href="https://ibb.co/0FSSLKN"><img src="https://i.ibb.co/HxssyCv/Screenshot-2024-04-22-113448.png" alt="Screenshot-2024-04-22-113448" border="0"></a>


- Screenshot berhasilnya menjalankan cargo run untuk mengirim 5 event memalui message brocker yang akan diproses oleh subscriber pada terminal publisher.
  <a href="https://ibb.co/7RBcLWj"><img src="https://i.ibb.co/yYKT7yd/Screenshot-2024-04-22-113538.png" alt="Screenshot-2024-04-22-113538" border="0"></a>

