1.	Jika diketahui 6 antrian proses (A, B, C, D, E, F) dengan waktu kedatangan secara bersamaan yaitu: 0. Lama eksekusi tiap – tiap antrian proses secara berurutan 1, 3, 7, 5, 5, 3. Hitunglah Turn Arround Time (TA) dengan menggunakan Teknik penjadwalan proses:
a.	First In First Out (F I F O)
b.	Shortest Job First (S J F)
c.	Round Robin jika diketahui Quantum = 2

2.	Dalam Penjadwalan proses terdapat tiga macam penjadwalan, sebutkan dan jelaskan disertai gambar!

3.	Sumber daya apa yang digunakan saat thread dibuat? Bagaimana mereka berbeda dari yang digunakan Ketika suatu proses dibuat?
4.	Output apa yang akan ditampilkan pada LINE A? Jelaskan!
      #include <sys/types.h>
      #include <stdio.h>
      #include <unistd.h>
      
      int value = 5;

      int main()
      {
        pid_t fork();
          if (pid == 0) { /*child process*/
            value += 15;
            return 0;
          }
          else if (pid >0){
            wait(NULL);
            printf("PARENT : value = %d",value);
            return 0;
          }	
      }
