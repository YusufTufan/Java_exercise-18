# Faktöriyel Hesaplama Programı
Bu program, kullanıcıdan bir sayı alarak bu sayının faktöriyelini hesaplar. Program, Java dilinde yazılmıştır.

## Açıklama
Bu Java programı, kullanıcıdan bir tam sayı alır ve bu sayının faktöriyelini hesaplar. Faktöriyel, bir sayının kendisi ile 1 arasındaki tüm tam sayıların çarpımıdır. Örneğin, 5 faktöriyeli (5!) = 5 * 4 * 3 * 2 * 1 = 120'dir.

Program, kullanıcıdan alınan sayının faktöriyelini hesaplamak için özyinelemeli (recursive) bir yöntem kullanır.

## Nasıl Çalıştırılır?
Programı çalıştırmak için aşağıdaki adımları izleyin:

1. Java SDK (JDK) kurulu olmalıdır.
2. Terminal veya komut istemcisini açın.
3. Proje dizinine gidin.
4. Java programını derleyin:
    ```bash
    javac Factorial.java
    ```
5. Derlenmiş programı çalıştırın:
    ```bash
    java Factorial
    ```
6. Program, bir sayı girmenizi isteyecektir. Bir sayı girin ve Enter tuşuna basın.
7. Program, girilen sayının faktöriyelini hesaplayacak ve sonucu ekrana yazdıracaktır.

## Gereksinimler
- Java SDK (JDK) kurulu olmalıdır.

## Örnek
### Giriş
```
Bana bir sayı söyle bende sana faktöriyelini hesaplayayım... 
5
```

### Çıkış
```
Sayın: 5 Faktöriyeli: 120
```

## Notlar
- Bu program sadece pozitif tam sayıların faktöriyelini hesaplar.
- Kullanıcı, programın çalışması sırasında kesinlikle pozitif bir tam sayı girmelidir.
- Program, kullanıcıdan sayı almak için `java.util.Scanner` sınıfını kullanır.
- Programın sonunda, `Scanner` nesnesi kapatılır.

Bu README dosyası, kullanıcılara programı çalıştırmak için gerekli adımları, örnek giriş ve çıkışları, gereksinimleri ve notları  anlatır.
