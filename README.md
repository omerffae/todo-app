# todo-app
# Todo App - Redux Entegrasyonlu Görev Yönetim Uygulaması

![Proje Görseli](./public/screenshot.png)

## Özellikler
- ✅ Redux ile global state yönetimi
- ✅ CRUD (Create, Read, Update, Delete) operasyonları
- ✅ Toast bildirim sistemi
- ✅ Modal üzerinden düzenleme
- ✅ Görev durum güncelleme (Tamamlandı/Devam Ediyor)
- ✅ Bootstrap ile responsive tasarım

## Teknolojiler
- ⚛️ React JS
- 🔄 Redux (State Management)
- 🎨 React Toastify (Bildirim Sistemi)
- 💅 Bootstrap 5 (Styling)
- ⚡ Vite (Build Tool)

## Kurulum
1. Repoyu klonlayın:
```bash
git clone https://github.com/omerffae/todo-app.git
```
2. Bağımlılıkları yükleyin:
```bash
npm install
```
3. Uygulamayı başlatın:
```bash
npm run server 
npm run dev
```

## Proje Yapısı
```
src/
├── components/
│   ├── Card/       # Görev kartı bileşeni
│   ├── List/       # Görev listesi bileşeni
│   └── Modal/      # Düzenleme modali
├── redux/
│   ├── actions/    # Redux action'ları
│   ├── reducers/   # Redux reducer'ları
│   └── store.js    # Redux store konfigürasyonu
└── utils/
    └── api.js      # API istekleri için axios instance
```

## Redux Mimarisi
```mermaid
graph TD
A[Action] --> B[Dispatch]
B --> C[Reducer]
C --> D[Store]
D --> E[Component]
E --> A
```

## Katkıda Bulunma
1. Forklayın (https://github.com/omerffae/todo-app.git)
2. Yeni branch oluşturun (`git checkout -b feature/fooBar`)
3. Değişikliklerinizi commit edin (`git commit -am 'Add some fooBar'`)
4. Push yapın (`git push origin feature/fooBar`)
5. Pull Request oluşturun

