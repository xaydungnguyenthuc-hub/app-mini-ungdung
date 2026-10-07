# Ứng dụng Tổng hợp — NTCons / VCM Portfolio

Cổng portfolio tập hợp các **ứng dụng quản lý, bán hàng, học tập và tính toán kết cấu** của NTCons / VCM, triển khai trên Vercel.

**Demo online:** [https://ungdungtonghop.vercel.app](https://ungdungtonghop.vercel.app)

---

## Tổng quan

| | |
|--|--|
| **Số app live** | 16 |
| **Hosting** | Vercel |
| **Source** | [xaydungnguyenthuc-hub](https://github.com/xaydungnguyenthuc-hub) |
| **File chính** | `index.html` (single-page portfolio) |

Mỗi ứng dụng chạy độc lập. Trang này chỉ là hub liên kết, có tìm kiếm theo tên / tag.

---

## Danh mục ứng dụng

### Thương mại, cửa hàng
| App | Link |
|-----|------|
| Vườn Của Mít | [vuoncuamit.vercel.app](https://vuoncuamit.vercel.app) |
| Bán hàng VCM | [banhangvcm.vercel.app](https://banhangvcm.vercel.app) |
| Kho hàng VCM | [khohangvcm.vercel.app](https://khohangvcm.vercel.app) |

### Quản lý nội bộ
| App | Link |
|-----|------|
| LogiKeep · Kho | [quanlykhont.vercel.app](https://quanlykhont.vercel.app) |
| Quản lý công trường | [congtruongntcons.vercel.app](https://congtruongntcons.vercel.app) |
| Quản lý học sinh | [quanlystudent.vercel.app](https://quanlystudent.vercel.app) |

### Quản lý học tập
| App | Link |
|-----|------|
| App Học Tập, luyện tập | [appluyentap.vercel.app](https://appluyentap.vercel.app) |
| **Ôn tập Luật Đấu thầu 2026** | [luatdauthau2026.vercel.app](https://luatdauthau2026.vercel.app) |

### Tính toán kết cấu
| App | Link |
|-----|------|
| KC BTCT TCVN 5574:2018 | [tinhkcbtct-5574-2018.vercel.app](https://tinhkcbtct-5574-2018.vercel.app) |
| Bê tông Pro | [tinhketcau_pro.vercel.app](https://tinhketcau_pro.vercel.app) |
| KC Dầm (Lovable) | [bangtinhdam55742018.lovable.app](https://bangtinhdam55742018.lovable.app) |
| KC Cột – Móng (Lovable) | [cotbtct5574-2018.lovable.app](https://cotbtct5574-2018.lovable.app) |
| KC BTCT (AppDeploy) | [cot-btct-v1-ft6vjo.v2.appdeploy.ai](https://cot-btct-v1-ft6vjo.v2.appdeploy.ai) |
| Tra tiêu chuẩn TNVL XD | [tra-cuu-tieu-chuan…](https://tra-cuu-tieu-chuan-thi-nghiem-vat-lieu-xay-dung-zcu8du.v2.appdeploy.ai) |

### Quản lý tuyển dụng
| App | Link |
|-----|------|
| Tuyển dụng NTCons | [qltuyendung.vercel.app](https://qltuyendung.vercel.app) |
| Hồ sơ ứng tuyển | [career-profile-pro…](https://career-profile-pro-g86ue6.v2.appdeploy.ai/) |

---

## Cấu trúc repo

```
ungdungtonghop/
├── index.html   # Trang portfolio (HTML/CSS/JS tĩnh)
└── README.md
```

Không cần build. Deploy trực tiếp lên Vercel / Netlify / GitHub Pages.

---

## Cách thêm app mới

1. Mở `index.html`
2. Thêm một thẻ `<article class="vcm-card">…</article>` vào section phù hợp
3. Cập nhật số lượng app trong hero + script tìm kiếm (ví dụ 16 → 17)
4. Commit & push — Vercel tự deploy

---

## Liên hệ

- GitHub: [xaydungnguyenthuc-hub](https://github.com/xaydungnguyenthuc-hub)
- Vercel team: **ntcons**

© 2025–2026 NTCons / VCM Portfolio
