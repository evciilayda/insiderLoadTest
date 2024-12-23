# Insider Load Test
Bu projede https://www.n11.com/  header da bulunan search modülü ve arama sonrası gidilen sonuçların listelendiği listeleme sayfasının yük altındaki davranışını incelemek adına Jmeter kullanılarak yük testi yapılmıştır.
Arama işlemi "cool lime" sözcüğü için full word(cool lime) ve partial olarak (cool or lime) için yapılmıştır.
Atılan isteklerin başarılı olduğunu kontrol etmek için çeşitli assertionlar kullanılmıştır. Bu çalışmada kullanılan assertionlar; response code, duration time, xpath assertion ve json assertiondur. Github Action yapısı kurulmuştur.

![image](https://github.com/user-attachments/assets/8a487b24-1f7f-4c4a-8cbc-b600aaaecc81)

