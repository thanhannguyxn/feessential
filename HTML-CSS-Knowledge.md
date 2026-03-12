# 📚 Toàn Bộ Kiến Thức HTML & CSS

---

# 🌟 PHẦN 1: HTML

## 1. 🌐 HTML Overview (Tổng quan HTML)

| Chủ đề | Nội dung |
|--------|----------|
| HTML là gì? | HyperText Markup Language - ngôn ngữ đánh dấu siêu văn bản |
| Lịch sử HTML | HTML 1.0 → HTML5 |
| Cấu trúc trang HTML | `<!DOCTYPE>`, `<html>`, `<head>`, `<body>` |
| HTML Boilerplate | Khung cơ bản của một trang HTML |
| Trình duyệt hoạt động | Browser parsing, rendering engine |
| Công cụ | VSCode, Sublime, IDE extensions |
| Inline vs Block | Phân biệt phần tử inline và block |
| Void/Self-closing tags | `<br>`, `<hr>`, `<img>`, `<input>` |
| Comments | `<!-- comment -->` |
| Character Encoding | `<meta charset="UTF-8">` |
| Meta tags cơ bản | `viewport`, `description`, `author` |

## 2. 🏗️ Semantic HTML

| Chủ đề | Nội dung |
|--------|----------|
| Semantic vs Non-semantic | `<div>/<span>` vs `<header>/<article>` |
| Layout Tags | `<header>`, `<footer>`, `<main>`, `<nav>` |
| Content Tags | `<article>`, `<section>`, `<aside>` |
| Text Semantic | `<strong>`, `<em>`, `<mark>`, `<time>`, `<cite>` |
| Figure & Media | `<figure>`, `<figcaption>` |
| Detail & Summary | `<details>`, `<summary>` |
| `<address>` | Thông tin liên lạc |
| `<blockquote>` & `<q>` | Trích dẫn |
| `<code>`, `<pre>`, `<kbd>` | Nội dung kỹ thuật |
| Tại sao dùng Semantic? | SEO, Accessibility, Readability |

## 3. 🧱 Elements and Attributes

### Text Elements
- Headings: `<h1>` → `<h6>`
- Paragraph: `<p>`
- Links: `<a href="" target="" rel="">`
- Lists: `<ul>`, `<ol>`, `<li>`, `<dl>`, `<dt>`, `<dd>`

### Media Elements
- Image: `<img src="" alt="" width="" height="">`
- Video: `<video controls autoplay loop muted>`
- Audio: `<audio controls>`
- Source: `<source src="" type="">`
- Iframe: `<iframe src="">`
- Canvas: `<canvas>`
- SVG: `<svg>`

### Global Attributes
| Attribute | Mô tả |
|-----------|-------|
| `id` | Định danh duy nhất |
| `class` | Gán class CSS |
| `style` | CSS inline |
| `title` | Tooltip |
| `data-*` | Custom data attributes |
| `hidden` | Ẩn phần tử |
| `tabindex` | Thứ tự tab |
| `contenteditable` | Cho phép chỉnh sửa |
| `draggable` | Kéo thả |
| `lang` | Ngôn ngữ |

### Link & Path
- Absolute vs Relative path
- `href`, `src`
- `target="_blank"`, `rel="noopener"`

## 4. 📊 Table, Form and Validation

### Table
| Tag | Mô tả |
|-----|-------|
| `<table>` | Tạo bảng |
| `<thead>`, `<tbody>`, `<tfoot>` | Phân vùng bảng |
| `<tr>` | Table row |
| `<th>` | Table header cell |
| `<td>` | Table data cell |
| `<caption>` | Tiêu đề bảng |
| `colspan`, `rowspan` | Gộp cột/hàng |
| `<colgroup>`, `<col>` | Định dạng cột |

### Form
| Tag/Attribute | Mô tả |
|---------------|-------|
| `<form action="" method="">` | Tạo form |
| `<input>` | Ô nhập liệu |
| `<textarea>` | Nhập văn bản dài |
| `<button>` | Nút bấm |
| `<select>`, `<option>`, `<optgroup>` | Dropdown |
| `<label for="">` | Nhãn cho input |
| `<fieldset>`, `<legend>` | Nhóm các field |
| `<datalist>` | Gợi ý nhập liệu |
| `<output>` | Hiển thị kết quả |

### Input Types
```
text, password, email, number, tel, url
date, time, datetime-local, month, week
checkbox, radio, range, color, file
submit, reset, button, hidden, search
```

### Validation
| Attribute | Mô tả |
|-----------|-------|
| `required` | Bắt buộc nhập |
| `minlength` / `maxlength` | Độ dài chuỗi |
| `min` / `max` | Giá trị số |
| `pattern` | Regex pattern |
| `type` | Tự động validate theo kiểu |
| `novalidate` | Tắt validation |
| `:valid` / `:invalid` | CSS pseudo-class |

## 5. ♿ Accessibility

| Chủ đề | Nội dung |
|--------|----------|
| ARIA là gì? | Accessible Rich Internet Applications |
| `role=""` | Định nghĩa vai trò phần tử |
| `aria-label` | Nhãn cho screen reader |
| `aria-labelledby` | Tham chiếu đến nhãn khác |
| `aria-describedby` | Mô tả thêm |
| `aria-hidden` | Ẩn khỏi screen reader |
| `aria-expanded` | Trạng thái mở/đóng |
| `aria-live` | Thông báo thay đổi động |
| `alt` text | Mô tả ảnh |
| Keyboard Navigation | `tabindex`, focus management |
| Skip Links | Nhảy qua nav đến nội dung chính |
| Color Contrast | Tỉ lệ tương phản màu sắc |
| WCAG | Web Content Accessibility Guidelines (A, AA, AAA) |
| Screen Reader | NVDA, JAWS, VoiceOver |
| Focus Indicator | Không được xóa outline |
| Semantic HTML | Tự nhiên hỗ trợ accessibility |

## 6. 🔍 SEO

| Chủ đề | Nội dung |
|--------|----------|
| Title Tag | `<title>` - quan trọng nhất |
| Meta Description | `<meta name="description">` |
| Meta Keywords | Ít dùng hiện nay |
| Heading Hierarchy | Dùng `<h1>` → `<h6>` đúng thứ tự |
| Alt Text | Tối ưu hóa hình ảnh |
| Canonical Tag | `<link rel="canonical">` |
| Open Graph | `og:title`, `og:image`, `og:description` |
| Twitter Card | `twitter:card`, `twitter:title` |
| Structured Data | Schema.org, JSON-LD |
| Sitemap | `sitemap.xml` |
| Robots | `<meta name="robots">`, `robots.txt` |
| Viewport Meta | Hỗ trợ mobile-first indexing |
| Page Speed | Ảnh hưởng trực tiếp đến ranking |
| Semantic HTML | Giúp bot đọc nội dung tốt hơn |
| Hreflang | Đa ngôn ngữ `<link rel="alternate" hreflang="">` |

---

# 🎨 PHẦN 2: CSS

## 1. 🌐 CSS Overview

| Chủ đề | Nội dung |
|--------|----------|
| CSS là gì? | Cascading Style Sheets - ngôn ngữ tạo kiểu cho HTML |
| Lịch sử | CSS1 → CSS2 → CSS3 (modules) |
| 3 cách dùng CSS | Inline, Internal (`<style>`), External (`.css` file) |
| Cú pháp | `selector { property: value; }` |
| CSS Reset vs Normalize | Loại bỏ style mặc định của trình duyệt |
| Browser DevTools | Inspect, debug CSS |
| Thứ tự ưu tiên | Inline > Internal > External |
| `!important` | Ghi đè mọi quy tắc (dùng cẩn thận) |
| CSS Variables | `--primary-color: red;` / `var(--primary-color)` |
| `:root` | Khai báo biến toàn cục |
| CSS Comments | `/* comment */` |

## 2. 🌊 Cascading and Inheritance

| Chủ đề | Nội dung |
|--------|----------|
| Cascading là gì? | Quy tắc áp dụng style theo tầng |
| Specificity | inline(1000) > id(100) > class(10) > tag(1) |
| Tính toán Specificity | `0,0,0,0` - 4 cột tính điểm |
| Source Order | Khai báo sau ghi đè khai báo trước |
| Inheritance | Thuộc tính cha truyền xuống con |
| Thuộc tính inherited | `color`, `font`, `visibility`... |
| Thuộc tính non-inherited | `margin`, `padding`, `border`... |
| `inherit` | Ép kế thừa từ cha |
| `initial` | Trả về giá trị mặc định |
| `unset` | Kết hợp inherit + initial |
| `revert` | Trả về style của trình duyệt |
| `all: unset` | Reset toàn bộ thuộc tính |

## 3. 🎯 Selector

### Basic Selectors
| Selector | Ví dụ | Mô tả |
|----------|-------|-------|
| Universal | `*` | Chọn tất cả |
| Type | `div` | Chọn theo tag |
| Class | `.box` | Chọn theo class |
| ID | `#header` | Chọn theo id |
| Attribute | `[type="text"]` | Chọn theo attribute |

### Combinator Selectors
| Selector | Ví dụ | Mô tả |
|----------|-------|-------|
| Descendant | `div p` | Con cháu bên trong |
| Child | `div > p` | Con trực tiếp |
| Adjacent Sibling | `h1 + p` | Anh em liền kề |
| General Sibling | `h1 ~ p` | Tất cả anh em phía sau |

### Pseudo-class
```
:hover        :focus        :active       :visited
:first-child  :last-child   :nth-child()  :nth-of-type()
:not()        :is()         :where()      :has()
:checked      :disabled     :enabled      :focus-visible
:empty        :root         :target       :focus-within
```

### Pseudo-element
```
::before      ::after       ::first-line  ::first-letter
::placeholder ::selection   ::marker      ::backdrop
```

## 4. 📦 Box Model

```
┌─────────────────────────────┐
│           MARGIN            │
│  ┌───────────────────────┐  │
│  │        BORDER         │  │
│  │  ┌─────────────────┐  │  │
│  │  │     PADDING     │  │  │
│  │  │  ┌───────────┐  │  │  │
│  │  │  │  CONTENT  │  │  │  │
│  │  │  └───────────┘  │  │  │
│  │  └─────────────────┘  │  │
│  └───────────────────────┘  │
└─────────────────────────────┘
```

| Chủ đề | Nội dung |
|--------|----------|
| `content` | Width & height thực của nội dung |
| `padding` | Khoảng cách trong (top/right/bottom/left) |
| `border` | Viền bao quanh padding |
| `margin` | Khoảng cách ngoài |
| `box-sizing: content-box` | Default - width chỉ tính content |
| `box-sizing: border-box` | Width = content + padding + border |
| `margin: auto` | Căn giữa block element |
| Margin Collapse | 2 margin dọc chập thành 1 |
| `outline` | Giống border nhưng không chiếm không gian |
| `overflow` | `visible`, `hidden`, `scroll`, `auto` |

## 5. 📐 Value and Unit

### Absolute Units
| Unit | Mô tả |
|------|-------|
| `px` | Pixel - phổ biến nhất |
| `pt` | Point (1pt = 1.33px) |
| `cm`, `mm`, `in` | Đơn vị in ấn |

### Relative Units
| Unit | Mô tả |
|------|-------|
| `%` | Phần trăm so với cha |
| `em` | Tương đối với font-size của chính nó |
| `rem` | Tương đối với font-size của `:root` |
| `vw` | 1% chiều rộng viewport |
| `vh` | 1% chiều cao viewport |
| `vmin` | 1% cạnh nhỏ hơn của viewport |
| `vmax` | 1% cạnh lớn hơn của viewport |
| `ch` | Chiều rộng ký tự "0" |
| `fr` | Fraction unit (dùng trong Grid) |

### CSS Functions
```css
calc()      clamp()     min()       max()
rgb()       rgba()      hsl()       hsla()
linear-gradient()       radial-gradient()
url()       var()       env()       translate()
```

## 6. 🎨 Common Properties

### Typography
| Property | Mô tả |
|----------|-------|
| `font-family` | Họ font chữ |
| `font-size` | Kích thước chữ |
| `font-weight` | Độ đậm (100-900, bold, normal) |
| `font-style` | `italic`, `oblique`, `normal` |
| `font-variant` | `small-caps` |
| `line-height` | Chiều cao dòng |
| `letter-spacing` | Khoảng cách chữ |
| `word-spacing` | Khoảng cách từ |
| `text-align` | `left`, `right`, `center`, `justify` |
| `text-decoration` | `underline`, `overline`, `line-through` |
| `text-transform` | `uppercase`, `lowercase`, `capitalize` |
| `text-indent` | Thụt đầu dòng |
| `text-shadow` | Đổ bóng chữ |
| `white-space` | `nowrap`, `pre`, `pre-wrap` |
| `word-break` | Xuống dòng từ |
| `@font-face` | Import font tùy chỉnh |
| Google Fonts | CDN font miễn phí |

### Background
| Property | Mô tả |
|----------|-------|
| `background-color` | Màu nền |
| `background-image` | Ảnh nền / gradient |
| `background-repeat` | `repeat`, `no-repeat`, `repeat-x/y` |
| `background-size` | `cover`, `contain`, `auto`, px/% |
| `background-position` | Vị trí ảnh nền |
| `background-attachment` | `fixed`, `scroll`, `local` |
| `background-clip` | `border-box`, `padding-box`, `content-box`, `text` |
| `background-origin` | Điểm bắt đầu tính vị trí |
| `background` shorthand | Viết tắt tất cả |
| `linear-gradient()` | Gradient tuyến tính |
| `radial-gradient()` | Gradient hướng tâm |
| `conic-gradient()` | Gradient hình nón |

### Border
| Property | Mô tả |
|----------|-------|
| `border-width` | Độ dày viền |
| `border-style` | `solid`, `dashed`, `dotted`, `double` |
| `border-color` | Màu viền |
| `border` shorthand | `1px solid red` |
| `border-radius` | Bo góc |
| `border-image` | Ảnh làm viền |
| `outline` | Viền ngoài border |
| `box-shadow` | Đổ bóng hộp |

## 7. 🏛️ Layout

### Inline Block & Position
| Chủ đề | Nội dung |
|--------|----------|
| `display` | `block`, `inline`, `inline-block`, `none` |
| `visibility` | `visible`, `hidden` |
| `position` | `static`, `relative`, `absolute`, `fixed`, `sticky` |
| `top/right/bottom/left` | Định vị phần tử |
| `z-index` | Thứ tự xếp chồng |
| `float` | `left`, `right`, `none` |
| `clear` | `both`, `left`, `right` |
| `clearfix` | Hack cho float layout |

### Flexbox
| Property | Giá trị |
|----------|---------|
| `display: flex` | Bật flexbox |
| `flex-direction` | `row`, `column`, `row-reverse`, `column-reverse` |
| `flex-wrap` | `nowrap`, `wrap`, `wrap-reverse` |
| `flex-flow` | Shorthand direction + wrap |
| `justify-content` | `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly` |
| `align-items` | `stretch`, `flex-start`, `flex-end`, `center`, `baseline` |
| `align-content` | Căn chỉnh nhiều dòng |
| `gap` | Khoảng cách giữa items |
| `flex-grow` | Tỉ lệ tăng trưởng |
| `flex-shrink` | Tỉ lệ co lại |
| `flex-basis` | Kích thước ban đầu |
| `flex` | Shorthand grow + shrink + basis |
| `align-self` | Căn chỉnh item riêng lẻ |
| `order` | Thứ tự hiển thị |

### CSS Grid
| Property | Giá trị |
|----------|---------|
| `display: grid` | Bật grid |
| `grid-template-columns` | Định nghĩa cột: `1fr 1fr 1fr` |
| `grid-template-rows` | Định nghĩa hàng |
| `grid-template-areas` | Đặt tên vùng |
| `gap` / `column-gap` / `row-gap` | Khoảng cách |
| `repeat()` | `repeat(3, 1fr)` |
| `minmax()` | `minmax(100px, 1fr)` |
| `auto-fill` / `auto-fit` | Tự động số cột |
| `grid-column` | `1 / 3` (span cột) |
| `grid-row` | `1 / 3` (span hàng) |
| `grid-area` | Gán vào vùng |
| `justify-items` | Căn ngang items |
| `align-items` | Căn dọc items |
| `place-items` | Shorthand cả 2 |

## 8. 📱 Responsive

### Meta Viewport
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### Media Query Breakpoints
```css
/* Mobile First */
@media (min-width: 576px) { }   /* SM */
@media (min-width: 768px) { }   /* MD */
@media (min-width: 992px) { }   /* LG */
@media (min-width: 1200px) { }  /* XL */
@media (min-width: 1400px) { }  /* XXL */

/* Desktop First */
@media (max-width: 1199px) { }
@media (max-width: 991px) { }
@media (max-width: 767px) { }
@media (max-width: 575px) { }
```

### Media Features
| Loại | Ví dụ |
|------|-------|
| `screen` | Màn hình |
| `print` | In ấn |
| `orientation: landscape/portrait` | Hướng màn hình |
| `prefers-color-scheme` | Dark/Light mode |
| `prefers-reduced-motion` | Giảm animation |
| `hover: none` | Thiết bị cảm ứng |

### Grid View Techniques
| Kỹ thuật | Mô tả |
|----------|-------|
| 12-column grid | Chia màn hình thành 12 cột |
| `auto-fill` + `minmax()` | Grid tự động responsive |
| `clamp()` | Font/size tự responsive |
| Fluid images | `max-width: 100%` |
| Container query | `@container` - responsive theo cha |

## 9. 🎬 Transition and Animation

### Transition
| Property | Mô tả |
|----------|-------|
| `transition-property` | Thuộc tính cần transition |
| `transition-duration` | Thời gian (s hoặc ms) |
| `transition-timing-function` | `ease`, `linear`, `ease-in`, `ease-out`, `ease-in-out`, `cubic-bezier()` |
| `transition-delay` | Độ trễ |
| `transition` shorthand | `all 0.3s ease` |

### Animation
```css
@keyframes slidein {
  from { transform: translateX(-100%); }
  to   { transform: translateX(0); }
}
```

| Property | Mô tả |
|----------|-------|
| `animation-name` | Tên @keyframes |
| `animation-duration` | Thời gian |
| `animation-timing-function` | Loại chuyển động |
| `animation-delay` | Độ trễ |
| `animation-iteration-count` | Số lần lặp / `infinite` |
| `animation-direction` | `normal`, `reverse`, `alternate` |
| `animation-fill-mode` | `forwards`, `backwards`, `both` |
| `animation-play-state` | `running`, `paused` |

### Transform
```css
/* 2D */
translate(x, y)    rotate(deg)
scale(x, y)        skew(x, y)

/* 3D */
translateZ()       rotateX()
rotateY()          perspective()
```

---

# 🅱️ PHẦN 3: Bootstrap 5

## Cài đặt
```html
<!-- CDN CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<!-- CDN JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

## Grid System
| Class | Breakpoint |
|-------|-----------|
| `col-` | < 576px (xs) |
| `col-sm-` | ≥ 576px |
| `col-md-` | ≥ 768px |
| `col-lg-` | ≥ 992px |
| `col-xl-` | ≥ 1200px |
| `col-xxl-` | ≥ 1400px |

```html
<div class="container">
  <div class="row">
    <div class="col-12 col-md-6 col-lg-4">...</div>
  </div>
</div>
```

## Spacing Utilities
```
m-{n}   p-{n}      → margin/padding all
mt-     mb-        → top/bottom
ms-     me-        → start(left)/end(right)
mx-     my-        → x-axis / y-axis
n = 0,1,2,3,4,5,auto
```

## Display & Flex Utilities
```
d-none     d-block    d-flex     d-grid
d-sm-flex  d-md-none  ...

flex-row      flex-column
justify-content-center    justify-content-between
align-items-center        flex-wrap
gap-2         gap-md-4
```

## Typography Utilities
```
h1 ~ h6           display-1 ~ display-6
fw-bold           fw-light        fw-semibold
fs-1 ~ fs-6       fst-italic
text-center       text-start      text-end
text-uppercase    text-lowercase  text-capitalize
text-truncate     text-wrap       text-nowrap
text-primary      text-danger     text-muted
```

## Color & Background
```
text-primary    text-secondary   text-success
text-danger     text-warning     text-info
text-dark       text-light       text-white
text-muted      text-body

bg-primary      bg-secondary     bg-success
bg-danger       bg-warning       bg-info
bg-dark         bg-light         bg-white
bg-transparent
```

## Components
| Component | Mô tả |
|-----------|-------|
| `Navbar` | Thanh điều hướng responsive |
| `Button` | btn, btn-primary, btn-outline-* |
| `Card` | Card với header/body/footer |
| `Modal` | Hộp thoại popup |
| `Carousel` | Slider ảnh |
| `Accordion` | Mở/đóng nội dung |
| `Tabs` | Điều hướng tab |
| `Dropdown` | Menu thả xuống |
| `Toast` | Thông báo nhỏ |
| `Alert` | Cảnh báo |
| `Badge` | Nhãn nhỏ |
| `Breadcrumb` | Đường dẫn điều hướng |
| `Pagination` | Phân trang |
| `Progress` | Thanh tiến trình |
| `Spinner` | Loading indicator |
| `Table` | Bảng với style |
| `Form` | Form controls đẹp |
| `List Group` | Danh sách có style |
| `Offcanvas` | Sidebar ẩn/hiện |

## Border & Shadow Utilities
```
border          border-0        border-top
border-primary  border-danger
rounded         rounded-pill    rounded-circle
rounded-0       rounded-1 ~ rounded-5

shadow-none     shadow-sm       shadow       shadow-lg
```

## Position & Sizing
```
position-relative   position-absolute
position-fixed      position-sticky

w-25    w-50    w-75    w-100   w-auto
h-25    h-50    h-75    h-100   h-auto

mw-100  mh-100
vw-100  vh-100
min-vw-100  min-vh-100
```

---

## 🗺️ Lộ Trình Học Gợi Ý

```
HTML Overview → Semantic HTML → Elements & Attributes
      ↓
Table & Form → Validation → Accessibility → SEO
      ↓
CSS Overview → Cascading & Inheritance → Selector
      ↓
Box Model → Value & Unit
      ↓
Common Properties (Typography → Background → Border)
      ↓
Layout (Inline Block → Flexbox → Grid)
      ↓
Responsive (Viewport → Media Query → Grid View)
      ↓
Transition & Animation
      ↓
Bootstrap 5
```

> 💡 **Tips:**
> - Học **Flexbox** và **Grid** thật chắc trước khi dùng Bootstrap
> - Dùng **rem** thay vì **px** để dễ responsive hơn
> - Luôn code theo hướng **Mobile First**
> - Practice trên [CSS Tricks](https://css-tricks.com) & [Flexbox Froggy](https://flexboxfroggy.com)
