# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1. | 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 | `Dizi manipüle edildi ve sıralandı.`
2. | 0, 1, 2, 3, 4 | <5> | 6, 7, 8, 9 | `root=5 seçildi ve küçük olanlar sola, büyük olanlar sağa yerleşti`
3. | 0, 1 | <2> | 3, 4 | `2. adımda soldaki grup için root=2 seçildi ve küçük olanlar sola, büyük olanlar sağa yerleşti`
4. | 6 | <7> | 8, 9 | `2. adımda sağdaki grup için root=7 seçildi ve küçük olanlar sola, büyük olanlar sağa yerleşti`
5. `Artık tüm gruplarda "leaf node"lara ulaşmış bulunuyoruz.`