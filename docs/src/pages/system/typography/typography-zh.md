# Typography（文字铸排）

<p class="description">用于控制对齐（alignment），封装（wrapping），以及字体权重（weight）等等的常用文本实用辅助工具的文档和示例。</p>

## 变体

{{"demo": "pages/system/typography/Variant.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ typography: 'subtitle2' }}>… // theme.typography.subtitle2
<Box sx={{ typography: 'body1' }}>…
<Box sx={{ typography: 'body2' }}>…
```

## 文本对齐（Text alignment）

{{"demo": "pages/system/typography/TextAlignment.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ textAlign: 'left' }}>…
<Box sx={{ textAlign: 'center' }}>…
<Box sx={{ textAlign: 'right' }}>…
```

## 字体权重（Font weight）

{{"demo": "pages/system/typography/FontWeight.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ fontWeight: 'light' }}>… // theme.typography.fontWeightLight
<Box sx={{ fontWeight: 'regular' }}>…
<Box sx={{ fontWeight: 'medium' }}>…
<Box sx={{ fontWeight: 500 }}>…
<Box sx={{ fontWeight: 'bold' }}>…
```

## 字体大小（Font size）

{{"demo": "pages/system/typography/FontSize.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ fontSize: 'default' }}>…  // theme.typography.fontSize
<Box sx={{ fontSize: 'h6.fontSize' }}>…
<Box sx={{ fontSize: 16 }}>…
```

## 字体

{{"demo": "pages/system/typography/FontStyle.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ fontStyle: 'normal' }}>…
<Box sx={{ fontStyle: 'italic' }}>…
<Box sx={{ fontStyle: 'oblique' }}>…
```

## Font family

{{"demo": "pages/system/typography/FontFamily.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ fontFamily: 'default' }}>…
<Box sx={{ fontFamily: 'Monospace' }}>…
```

## 字母间距

{{"demo": "pages/system/typography/LetterSpacing.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ letterSpacing: 6 }}>…
<Box sx={{ letterSpacing: 10 }}>…
```

## 行高

{{"demo": "pages/system/typography/LineHeight.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ lineHeight: 'normal' }}>…
<Box sx={{ lineHeight: 10 }}>…
```

## API

```js
import { typography } from '@mui/system';
```

| 导入名称            | 属性              | CSS 属性                                                                                       | Theme key                                                              |
|:--------------- |:--------------- |:-------------------------------------------------------------------------------------------- |:---------------------------------------------------------------------- |
| `typography`    | `typography`    | `font-family`, `font-weight`, `font-size`, `line-height`, `letter-spacing`, `text-transform` | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `fontFamily`    | `fontFamily`    | `font-family`                                                                                | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `fontSize`      | `fontSize`      | `font-size`                                                                                  | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `fontStyle`     | `fontStyle`     | `font-style`                                                                                 | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `fontWeight`    | `fontWeight`    | `font-weight`                                                                                | [`typography`](/customization/default-theme/?expand-path=$.typography) |
| `letterSpacing` | `letterSpacing` | `letter-spacing`                                                                             | none                                                                   |
| `lineHeight`    | `lineHeight`    | `line-height`                                                                                | none                                                                   |
| `textAlign`     | `textAlign`     | `text-align`                                                                                 | none                                                                   |
