# Adam Asmaca

Konsol tabanlı basit bir **adam asmaca** oyunu. Rastgele seçilen Türkiye ili, harf harf tahmin edilerek bulunmaya çalışılır.

## Nasıl oynanır?

- Oyun başında rastgele bir il seçilir; kelime uzunluğu kadar `_` gösterilir.
- Tahmin hakkı: **kelime uzunluğu − 2**
- Doğru harf girildiğinde ilgili pozisyonlar açılır; yanlış harfte hak azalır.
- Tüm harfleri doğru tahmin edersen kazanırsın; haklar biterse kaybedersin.

## Gereksinimler

- [.NET Framework 4.6.1](https://dotnet.microsoft.com/download/dotnet-framework) veya üzeri
- Windows: [Visual Studio](https://visualstudio.microsoft.com/) (önerilen) veya MSBuild

## Çalıştırma

### Visual Studio

1. `adam asmaca.sln` dosyasını açın.
2. **Debug** → **Start Without Debugging** (Ctrl+F5) veya **Start** (F5).

### Komut satırı (MSBuild)

```bash
msbuild "adam asmaca.sln" /p:Configuration=Release
"adam asmaca/bin/Release/adam asmaca.exe"
```

## Proje yapısı

```
adam-asmaca/
├── adam asmaca.sln
└── adam asmaca/
    ├── Program.cs          # Oyun mantığı
    ├── adam asmaca.csproj
    └── App.config
```

## Lisans

Bu proje eğitim amaçlıdır. İstediğiniz gibi kullanabilir ve geliştirebilirsiniz.

---

*Muhammed Beşir Kesen*
