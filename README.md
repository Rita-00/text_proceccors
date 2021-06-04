# text_proceccors
Файл text1.txt
![2021-06-04 (7)](https://user-images.githubusercontent.com/56391887/120743964-54201e00-c53d-11eb-8574-ebf4e1378379.png)
tail -n 40 text1.txt > text2.txt
![2021-06-04 (72)](https://user-images.githubusercontent.com/56391887/120744013-71ed8300-c53d-11eb-9b94-1fabaf47b738.png)
head -n 10 text2.txt > text3.txt
![2021-06-04 (712)](https://user-images.githubusercontent.com/56391887/120744079-947f9c00-c53d-11eb-96f9-ab5b9009da97.png)
sed -r 's/koko/kuku/g' text2.txt | grep 'kuku' | head -n 3 >> text3.txt
![2021-06-04 (71)](https://user-images.githubusercontent.com/56391887/120744105-a3664e80-c53d-11eb-93ef-9b08c02a3f41.png)
sort text3.txt | uniq -c
![image](https://user-images.githubusercontent.com/56391887/120744167-c4c73a80-c53d-11eb-8d2f-e77865d78e79.png)
