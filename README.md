
​```
### vite 图片引用
export function getImageUrl(url: string) {
  return new URL(`/src/assets/${url}`, import.meta.url).href
}
​
```
