# OneZero - Frontend Müsahibə Tapşırığı

## Tapşırığın Təsviri

Bu tapşırığın məqsədi verilmiş URL-dən məlumat alaraq həmin datanı Redux-da saxlamaq və ekranda tələb olunan dizayna uyğun olaraq dinamik şəkildə göstərməkdir. Aşağıda tapşırığın detalları və addım-addım icrası izah olunub.

## Tələblər

1. **URL-dən Məlumatın Alınması**:

   - Verilmiş URL-ə sorğu göndərin və məlumatı alın.(`http://localhost:5000/menu.json`)
   - Alınan məlumatı Redux storunda saxlayın.

2. **Kateqoriyaların Dinamik Göstərilməsi**:

   - Məlumat əsasında kateqoriyalar dinamik olaraq ekranda göstərilməlidir.
   - Keteqoriyalar ve məhsullar `isArchived` görə filter olunmalıdır.
   - Hər bir kateqoriya kliklənə bilən bir düymə və ya tab kimi təqdim olunmalıdır.
   - Dizayn Linki: `https://www.figma.com/design/Bx81HNqNgvOlFwS0sYQCK5/Front-Task?node-id=1-170&node-type=FRAME&t=W6RcRILVWMn3tv3w-0`

3. **Məhsulların Kateqoriya Üzrə Göstərilməsi**:

   - Hər hansı bir kateqoriyaya klik etdikdə, yalnız həmin kateqoriyanın məhsulları göstərilməlidir.
   - "All" (Hamısı) seçildikdə, bütün kateqoriyaların məhsulları başlıqları ilə birlikdə göstərilməlidir.

4. **Məhsulun Kliklə Modaldə Açılması**:
   - Hər hansı bir məhsula klik etdikdə, həmin məhsulun detalları ilə bağlı modal pəncərə açılmalıdır.

## Tələb Olunan Texnologiyalar

- Redux Toolkit
- SCSS
