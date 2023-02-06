# example-failing-tailwind-no-custom-classname
Failure with interactions: tailwindcss/no-custom-classname and tailwindcss-radix

Setup:
1. yarn install
2. yarn lint

Lint error:
```
  39:7  error  Classname 'translate-x-radix-toast-swipe-move-x' is not a Tailwind CSS class!  tailwindcss/no-custom-classname
  39:7  error  Classname 'radix-state-closed:animate-hide' is not a Tailwind CSS class!       tailwindcss/no-custom-classname
  39:7  error  Classname 'radix-state-open:animate-slideIn' is not a Tailwind CSS class!      tailwindcss/no-custom-classname
  43:9  error  Classname 'drop-shadow-sharp/25' is not a Tailwind CSS class!                  tailwindcss/no-custom-classname
  43:9  error  Classname 'hover:drop-shadow-sharp/75' is not a Tailwind CSS class!            tailwindcss/no-custom-classname
```

Using project from: https://github.com/lucasjungdeveloper/radix-tailwind

Note from tailwindcss-radix plugin maintainer: https://github.com/ecklf/tailwindcss-radix/issues/32#issuecomment-1398916482
