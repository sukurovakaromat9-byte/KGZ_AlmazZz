<!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:wght@400;600;700&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "primary-container": "#005f73",
                        "on-surface-variant": "#3f484c",
                        "on-surface": "#191c1d",
                        "on-primary-fixed": "#001f27",
                        "secondary-fixed-dim": "#ffb4ab",
                        "tertiary-container": "#7e492b",
                        "outline": "#6f797c",
                        "error": "#ba1a1a",
                        "on-error-container": "#93000a",
                        "on-secondary-container": "#fffbff",
                        "on-primary-container": "#91d7ee",
                        "primary-fixed-dim": "#8bd1e8",
                        "inverse-primary": "#8bd1e8",
                        "background": "#f8f9fa",
                        "error-container": "#ffdad6",
                        "on-primary-fixed-variant": "#004e5f",
                        "surface-container-lowest": "#ffffff",
                        "surface-container": "#edeeef",
                        "on-secondary-fixed": "#410002",
                        "on-error": "#ffffff",
                        "surface-variant": "#e1e3e4",
                        "secondary-container": "#de2e2c",
                        "on-tertiary-fixed": "#331100",
                        "outline-variant": "#bfc8cc",
                        "on-secondary-fixed-variant": "#93000d",
                        "on-secondary": "#ffffff",
                        "secondary": "#b90c17",
                        "on-background": "#191c1d",
                        "surface-tint": "#13677b",
                        "surface-container-high": "#e7e8e9",
                        "on-tertiary": "#ffffff",
                        "on-primary": "#ffffff",
                        "secondary-fixed": "#ffdad6",
                        "tertiary-fixed": "#ffdbca",
                        "surface": "#f8f9fa",
                        "on-tertiary-container": "#ffbe9c",
                        "inverse-surface": "#2e3132",
                        "primary-fixed": "#b2ebff",
                        "tertiary-fixed-dim": "#feb691",
                        "surface-bright": "#f8f9fa",
                        "tertiary": "#623317",
                        "surface-container-low": "#f3f4f5",
                        "primary": "#004655",
                        "surface-container-highest": "#e1e3e4",
                        "on-tertiary-fixed-variant": "#6b3a1d",
                        "surface-dim": "#d9dadb",
                        "inverse-on-surface": "#f0f1f2"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "gutter": "24px",
                        "margin-desktop": "40px",
                        "unit": "8px",
                        "margin-mobile": "16px",
                        "container-max": "1280px",
                        "section-gap": "120px"
                    },
                    "fontFamily": {
                        "body-md": ["Manrope"],
                        "label-sm": ["Manrope"],
                        "headline-lg": ["Noto Serif"],
                        "display-xl": ["Noto Serif"],
                        "body-lg": ["Manrope"],
                        "headline-md": ["Noto Serif"]
                    },
                    "fontSize": {
                        "body-md": ["16px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "label-sm": ["14px", {"lineHeight": "1.0", "letterSpacing": "0.05em", "fontWeight": "600"}],
                        "headline-lg": ["40px", {"lineHeight": "1.2", "fontWeight": "600"}],
                        "display-xl": ["64px", {"lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                        "body-lg": ["18px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "headline-md": ["28px", {"lineHeight": "1.3", "fontWeight": "600"}]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
            display: inline-block;
            line-height: 1;
            text-transform: none;
            letter-spacing: normal;
            word-wrap: normal;
            white-space: nowrap;
            direction: ltr;
        }
        .alpine-overlay {
            background: linear-gradient(to bottom, rgba(0, 95, 115, 0.4) 0%, rgba(25, 28, 29, 0.8) 100%);
        }
        .oimok-pattern {
            opacity: 0.05;
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M30 0l30 30-30 30L0 30z' fill='%23005f73' fill-opacity='1' fill-rule='evenodd'/%3E%3C/svg%3E");
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background text-on-surface font-body-md selection:bg-primary-container selection:text-on-primary-container">
<header class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-6 h-16 bg-[#F8F9FA] shadow-[0_4px_20px_-2px_rgba(0,64,82,0.08)] border-b border-stone-200">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#005F73]">menu</span>
<span class="text-2xl font-bold tracking-widest uppercase text-[#005F73] font-serif">Kyrgyzstan</span>
</div>
<nav class="hidden md:flex gap-8 items-center">
<a class="font-serif text-[#005F73] font-bold border-b-2 border-[#D66853]" href="#">Home</a>
<a class="font-serif text-stone-600 hover:text-[#005F73] transition-all" href="#">Lakes</a>
<a class="font-serif text-stone-600 hover:text-[#005F73] transition-all" href="#">Culture</a>
<a class="font-serif text-stone-600 hover:text-[#005F73] transition-all" href="#">Nature</a>
<a class="font-serif text-stone-600 hover:text-[#005F73] transition-all" href="#">Cuisine</a>
</nav>
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#005F73]">language</span>
<button class="bg-primary text-on-primary px-4 py-2 rounded-lg font-label-sm hover:translate-y-[-2px] transition-transform active:scale-95">План Поездки</button>
</div>
</header>
<main>
<section class="relative h-screen flex items-center justify-center overflow-hidden">
<div class="absolute inset-0 z-0">
<img alt="Kyrgyz Mountains" class="w-full h-full object-cover" data-alt="Majestic snow-capped peaks of the Tian Shan mountains reflecting in a crystal clear alpine lake at dawn with soft blue and pink light" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDm-iftHQtHeOw71VO3LFNYuBeDoda5qLHVMbH4JYi8HnGMIdj56IXj_EZtUMO8ZVV6YaguGtiJRIK8514wDL_VB2J7hZfQkUcusELEsZappG6zRv0-k2NEfHlR4qhAcWw8NO90BxcDUT7fxJMxC3O_wN_g5H8ca5g2R9K-cSBiOjQTVatBiGGuHszVX6BjVM8Vb9rOqbJE85rkDJeXd9sob0sB1iohzJ8zGplE5nausMXyTb7VsQeuCyOl14-upQCT5ix_N4A-Buc"/>
<div class="absolute inset-0 alpine-overlay"></div>
</div>
<div class="relative z-10 text-center px-4 max-w-5xl">
<span class="inline-block px-4 py-1 mb-6 rounded-full bg-secondary text-on-secondary font-label-sm uppercase tracking-widest">Откройте Величие</span>
<h1 class="font-display-xl text-white text-display-xl mb-6">Кыргызстан: Страна Небесных Гор</h1>
<p class="font-body-lg text-white/90 text-body-lg max-w-2xl mx-auto mb-10">
                    Почувствуйте свободу кочевой жизни среди бескрайних степей и бирюзовых высокогорных озер в самом сердце Центральной Азии.
                </p>
<div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
<button class="bg-primary-fixed text-on-primary-fixed px-8 py-4 rounded-xl font-label-sm flex items-center gap-2 hover:shadow-xl transition-all">
                        Начать Путешествие <span class="material-symbols-outlined">arrow_forward</span>
</button>
</div>
</div>
<div class="absolute bottom-10 left-1/2 -translate-x-1/2 animate-bounce">
<span class="material-symbols-outlined text-white text-4xl">expand_more</span>
</div>
</section>
<section class="py-section-gap px-6 max-w-container-max mx-auto">
<div class="text-center mb-16">
<h2 class="font-headline-lg text-primary text-headline-lg mb-4">Лучшие Направления</h2>
<div class="w-24 h-1 bg-secondary mx-auto"></div>
</div>
<div class="grid grid-cols-1 md:grid-cols-12 gap-6 h-auto md:h-[700px]">
<div class="md:col-span-8 group relative overflow-hidden rounded-3xl shadow-lg border border-stone-100">
<img alt="Issyk-Kul Lake" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" data-alt="Wide panoramic view of Issyk-Kul lake with sandy shores and distant snow-capped mountains under a bright blue sky" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCzKLWq7vg0r9OjsSPhWgRXOjKBXySjuGlfY0nkG75LEurVMLU-gTTcfljMBHnqA22uTae0-uXOGF_k9wKkJoBEh1i3-R1vZfhKHE7-siT3co8kOLP-UC6uadwA7SQI5So7sCSNI8ywaY6Nmq85XgazZ6fDKeAKQXJ6xcAcQ0b8MPqNtWQ6NneysMd9IxFEWfSy4Yn7DNHlc7VmARG6ppltSC9Azx81xW4y8kwQL7wFyMDyBijHacaVdfaECssiYQG-rf-HclqF-4U"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent flex flex-col justify-end p-8">
<span class="text-secondary-fixed font-label-sm mb-2">Озера</span>
<h3 class="text-white font-headline-md text-headline-md mb-2">Иссык-Куль</h3>
<p class="text-white/80 font-body-md max-w-md">Жемчужина Тянь-Шаня и второе по величине высокогорное озеро в мире.</p>
</div>
</div>
<div class="md:col-span-4 grid grid-rows-2 gap-6">
<div class="group relative overflow-hidden rounded-3xl shadow-lg border border-stone-100">
<img alt="Ala-Archa" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" data-alt="Narrow rocky canyon with a rushing mountain stream and sharp granite peaks in Ala-Archa National Park" src="data:image/jpeg;base64,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"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent flex flex-col justify-end p-6">
<h3 class="text-white font-headline-md text-body-lg">Ала-Арча</h3>
</div>
</div>
<div class="group relative overflow-hidden rounded-3xl shadow-lg border border-stone-100">
<img alt="Song-Kul" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" data-alt="Nomadic yurt camp at the edge of Song-Kul lake during sunset with grazing horses and vast green plains" src="data:image/jpeg;base64,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"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent flex flex-col justify-end p-6">
<h3 class="text-white font-headline-md text-body-lg">Сон-Куль</h3>
</div>
</div>
</div>
</div>
</section>
<section class="py-section-gap relative bg-surface-container-low overflow-hidden">
<div class="absolute top-0 right-0 w-1/2 h-full oimok-pattern pointer-events-none"></div>
<div class="max-w-container-max mx-auto px-6 grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
<div class="relative">
<div class="rounded-3xl overflow-hidden shadow-2xl relative z-10 aspect-[4/5]">
<div class="absolute -bottom-10 -right-10 w-64 h-64 rounded-3xl overflow-hidden border-8 border-background shadow-xl hidden md:block">
<img alt="Kyrgyz People" class="w-full h-full object-cover" data-alt="Portrait of a smiling elderly Kyrgyz man in traditional kalpak hat with a background of rolling green hills" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAlRwm14dtiCQ-uq0rV2lqcXsSbmihe66mjGfBvHeEoj8B2YVTpEqHIfZd4EAgNWu_AyBtUtPsoDF5Gw559X4s0il-q0r7uMON1m6SRr4J_QY-kgQd48QEj3fWrBu9fOCxPt4w4apGFVjDuap2dIKxNFbuftYhgCLWEdGQwfCMDZZIWEbDjk7mcQIPzjGTNDAvJOsRH66hEAu7yBf25gPdJ7QSFili1Q2ahDZTC_3F9bEHE7NQl4bO41SxEbQQZ1Q5cKHxJka2bZRI"/>
</div>
</div>
<div>
<span class="text-primary font-label-sm tracking-widest uppercase mb-4 block">Культурное Наследие</span>
<h2 class="font-headline-lg text-on-surface text-display-xl mb-8 leading-tight">Почувствуйте Дух Кочевника</h2>
<p class="font-body-lg text-on-surface-variant mb-8">
                        Гостеприимство – сердце кыргызской культуры. Проведите ночь в традиционной юрте, попробуйте свежий кумыс и услышьте эпические сказания Манаса под звездным небом высокогорья.
                    </p>
<ul class="space-y-6 mb-10">
<li class="flex items-start gap-4">
<span class="material-symbols-outlined text-secondary text-3xl">home</span>
<div>
<h4 class="font-bold text-primary">Проживание в Юртах</h4>
<p class="text-on-surface-variant">Аутентичный опыт жизни в гармонии с природой.</p>
</div>
</li>
<li class="flex items-start gap-4">
<span class="material-symbols-outlined text-secondary text-3xl">restaurant</span>
<div>
<h4 class="font-bold text-primary"><a href="undex2.html">Национальная Кухня</a></h4>
<p class="text-on-surface-variant">Традиционные блюда: бешбармак, боорсок и чай с горными травами.</p>
</div>
</li>
<li class="flex items-start gap-4">
<span class="material-symbols-outlined text-secondary text-3xl">festival</span>
<div>
<h4 class="font-bold text-primary">Конные Игры</h4>
<p class="text-on-surface-variant">Мастерство наездников в захватывающих состязаниях Көк-бөрү.</p>
</div>
</li>
</ul>
<button class="bg-primary text-on-primary px-8 py-4 rounded-xl font-label-sm shadow-lg hover:shadow-primary/20 transition-all"><a href="undex5.html">узнать больше</a></button>
</div>
</div>
</section>
<section class="py-section-gap px-6 max-w-container-max mx-auto">
<div class="text-center mb-16">
<h2 class="font-headline-lg text-primary text-headline-lg mb-4">Почему Стоит Посетить?</h2>
<div class="w-24 h-1 bg-secondary mx-auto"></div>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-12">
<div class="text-center p-8 rounded-3xl bg-surface-container hover:bg-surface-container-high transition-colors border border-stone-100">
<div class="w-16 h-16 bg-primary-fixed-dim rounded-full flex items-center justify-center mx-auto mb-6">
<span class="material-symbols-outlined text-primary text-3xl">terrain</span>
</div>
<h3 class="font-headline-md text-primary mb-4">Нетронутая Природа</h3>
<p class="text-on-surface-variant">Более 90% территории страны занимают горы, предлагая бесконечные возможности для треккинга.</p>
</div>
<div class="text-center p-8 rounded-3xl bg-surface-container hover:bg-surface-container-high transition-colors border border-stone-100">
<div class="w-16 h-16 bg-primary-fixed-dim rounded-full flex items-center justify-center mx-auto mb-6">
<span class="material-symbols-outlined text-primary text-3xl">verified_user</span>
</div>
<h3 class="font-headline-md text-primary mb-4">Безвизовый Режим</h3>
<p class="text-on-surface-variant">Кыргызстан открыт для граждан многих стран, делая путешествие доступным и легким.</p>
</div>
<div class="text-center p-8 rounded-3xl bg-surface-container hover:bg-surface-container-high transition-colors border border-stone-100">
<div class="w-16 h-16 bg-primary-fixed-dim rounded-full flex items-center justify-center mx-auto mb-6">
<span class="material-symbols-outlined text-primary text-3xl">favorite</span>
</div>
<h3 class="font-headline-md text-primary mb-4">Искренние Люди</h3>
<p class="text-on-surface-variant">Традиции гостеприимства делают каждого туриста желанным гостем в любом доме.</p>
</div>
</div>
</section><!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:wght@400;600;700&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "primary-container": "#005f73",
                        "on-surface-variant": "#3f484c",
                        "on-surface": "#191c1d",
                        "on-primary-fixed": "#001f27",
                        "secondary-fixed-dim": "#ffb4ab",
                        "tertiary-container": "#7e492b",
                        "outline": "#6f797c",
                        "error": "#ba1a1a",
                        "on-error-container": "#93000a",
                        "on-secondary-container": "#fffbff",
                        "on-primary-container": "#91d7ee",
                        "primary-fixed-dim": "#8bd1e8",
                        "inverse-primary": "#8bd1e8",
                        "background": "#f8f9fa",
                        "error-container": "#ffdad6",
                        "on-primary-fixed-variant": "#004e5f",
                        "surface-container-lowest": "#ffffff",
                        "surface-container": "#edeeef",
                        "on-secondary-fixed": "#410002",
                        "on-error": "#ffffff",
                        "surface-variant": "#e1e3e4",
                        "secondary-container": "#de2e2c",
                        "on-tertiary-fixed": "#331100",
                        "outline-variant": "#bfc8cc",
                        "on-secondary-fixed-variant": "#93000d",
                        "on-secondary": "#ffffff",
                        "secondary": "#b90c17",
                        "on-background": "#191c1d",
                        "surface-tint": "#13677b",
                        "surface-container-high": "#e7e8e9",
                        "on-tertiary": "#ffffff",
                        "on-primary": "#ffffff",
                        "secondary-fixed": "#ffdad6",
                        "tertiary-fixed": "#ffdbca",
                        "surface": "#f8f9fa",
                        "on-tertiary-container": "#ffbe9c",
                        "inverse-surface": "#2e3132",
                        "primary-fixed": "#b2ebff",
                        "tertiary-fixed-dim": "#feb691",
                        "surface-bright": "#f8f9fa",
                        "tertiary": "#623317",
                        "surface-container-low": "#f3f4f5",
                        "primary": "#004655",
                        "surface-container-highest": "#e1e3e4",
                        "on-tertiary-fixed-variant": "#6b3a1d",
                        "surface-dim": "#d9dadb",
                        "inverse-on-surface": "#f0f1f2"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "gutter": "24px",
                        "margin-desktop": "40px",
                        "unit": "8px",
                        "margin-mobile": "16px",
                        "container-max": "1280px",
                        "section-gap": "120px"
                    },
                    "fontFamily": {
                        "body-md": ["Manrope"],
                        "label-sm": ["Manrope"],
                        "headline-lg": ["Noto Serif"],
                        "display-xl": ["Noto Serif"],
                        "body-lg": ["Manrope"],
                        "headline-md": ["Noto Serif"]
                    },
                    "fontSize": {
                        "body-md": ["16px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "label-sm": ["14px", {"lineHeight": "1.0", "letterSpacing": "0.05em", "fontWeight": "600"}],
                        "headline-lg": ["40px", {"lineHeight": "1.2", "fontWeight": "600"}],
                        "display-xl": ["64px", {"lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                        "body-lg": ["18px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "headline-md": ["28px", {"lineHeight": "1.3", "fontWeight": "600"}]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 48;
        }
        .oimok-border {
            mask-image: radial-gradient(circle at 10px 10px, transparent 10px, black 11px);
            mask-repeat: repeat;
            mask-size: 20px 20px;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background text-on-background font-body-md">
<!-- TopAppBar -->
<header class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-6 h-16 bg-[#F8F9FA] dark:bg-stone-950 border-b border-stone-200 dark:border-stone-800 shadow-[0_4px_20px_-2px_rgba(0,64,82,0.08)]">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#005F73] dark:text-teal-400 cursor-pointer">menu</span>
<span class="text-2xl font-bold tracking-widest uppercase text-[#005F73] dark:text-teal-500 font-serif">Kyrgyzstan</span>
</div>
<nav class="hidden md:flex gap-8 items-center">
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Home</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Lakes</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Culture</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Nature</a>
<a class="font-serif text-[#005F73] font-bold border-b-2 border-[#D66853]" href="#">Cuisine</a>
</nav>
<span class="material-symbols-outlined text-[#005F73] dark:text-teal-400 cursor-pointer">language</span>
</header>
<main class="pt-16 pb-32">
<!-- Hero Section -->
<section class="relative h-[707px] flex items-center justify-center overflow-hidden">
<div class="absolute inset-0 bg-gradient-to-b from-primary/40 to-primary/80 z-10"></div>
<img class="absolute inset-0 w-full h-full object-cover" data-alt="close-up of traditional Kyrgyz table spread with fresh Boorsoks, Beshbarmak in a ceramic bowl, and tea in a sunlit yurt" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCZXMYnFNrQ_U0NuyoDt-_p-GvOrH2OckipFIJff57kOOPDCxrOcRXIscBuIlxnsyiwcashbpnVy5ynG2pxV0uAwVD4e2sbZnxJvygX642QVASvXuV7SI3JajeA4JnT6AvzMl1CirtknKlPtAUMYsseIFkGn-m8dRM8D7pX2ZZ2C7pIF2SrNXCd9eo3yRFbVKOuQBKPrfAutSuQPYiiWfdTES_L0fArkecRRpntWwHPBCMfns58VyPLvgtX8FsODtsbsedDxuZSksY"/>
<div class="relative z-20 text-center px-6 max-w-4xl">
<h1 class="font-display-xl text-display-xl text-surface-container-lowest mb-6">Вкус Кочевой Свободы</h1>
<p class="font-body-lg text-body-lg text-surface-container-low max-w-2xl mx-auto">Откройте для себя богатое наследие кыргызской кухни, где каждый ингредиент пропитан духом гор и гостеприимством степи.</p>
</div>
</section>
<!-- Cultural Divider -->
<div class="flex items-center justify-center my-16 px-8">
<div class="h-px bg-secondary-container flex-grow max-w-xs"></div>
<div class="mx-6 text-secondary">
<span class="material-symbols-outlined text-4xl" data-weight="fill">temple_buddhist</span>
</div>
<div class="h-px bg-secondary-container flex-grow max-w-xs"></div>
</div>
<!-- Featured Dishes Bento Grid -->
<section class="max-w-7xl mx-auto px-8 mb-section-gap">
<div class="grid grid-cols-1 md:grid-cols-12 gap-8">
<!-- Beshbarmak -->
<div class="md:col-span-8 group relative overflow-hidden rounded-3xl shadow-[0_4px_24px_rgba(0,64,82,0.06)] bg-surface-container-lowest">
<div class="flex flex-col md:flex-row h-full">
<div class="md:w-1/2 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="Beshbarmak dish with hand-pulled noodles and tender horse meat topped with onions in a rich broth" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDUBLqR_pZg3nB5Fyg630r2DXDGUniyoVNWKc5JNQiSygWqGYCRxQGJiRR5JFqFitzW0G3_KZ4qYsNSTMtc-1mMjAC3ZOHKkxjekYsh1l336NuvRvNuVaWToJxS3kWj_gFSIrcp6nS7O_nGfqEMXR4ayl8fHrpha4F5wehVsqVUvQ8d6Rix7jBeoV4r6C3p78semhfTFO3cEq7KTkL0T1o6yboQZ-NOaVG-tqz8Mzewtj9Ytl82En8Y-OEClMZ2ct1xz6imY5Sxg2s"/>
</div>
<div class="md:w-1/2 p-10 flex flex-col justify-center">
<span class="text-secondary font-label-sm uppercase mb-4 tracking-widest">Король Стола</span>
<h2 class="font-headline-lg text-headline-lg mb-4 text-primary">Beshbarmak</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-6">«Пять пальцев» — сердце кыргызского застолья. Тончайшая лапша ручной лепки, нежнейшее мясо (конина или баранина) и насыщенный луковый соус «чык».</p>
<div class="flex gap-2">
<span class="bg-tertiary-fixed text-on-tertiary-fixed-variant px-3 py-1 rounded-full text-xs font-bold uppercase">Сытное</span>
<span class="bg-primary-fixed text-on-primary-fixed-variant px-3 py-1 rounded-full text-xs font-bold uppercase">Традиционное</span>
</div>
</div>
</div>
</div>
<!-- Boorsoks -->
<div class="md:col-span-4 group relative overflow-hidden rounded-3xl shadow-[0_4px_24px_rgba(0,64,82,0.06)] bg-surface-container-lowest">
<img class="w-full h-64 object-cover" data-alt="golden fried Boorsok dough pieces piled high in a traditional wooden basket with soft lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB4YUN062rgq1aIk9LL7fs9C05sR-Rqz5KZNCDbgNM_09OfLiVts9J4hKbjsHQqA4Id2QaHPL22o1n-VjJCzFm39gjj858xUrCTLeBOuqiqPu-GBHJxGNTI4j48n_6refBJ0LY5uPsN2kQla5CU5U_tuaKWTI9s5FCAXFjLZI9VyPukxZyBwMYX_N3fX3eK3XqsWNRAwbt-cSSuBfONb_aybThbpveGHqn_Q1UC9C86cYHXUngecDT5QpIgbG2vbcKRlBxHMLQOa8Y"/>
<div class="p-8">
<h2 class="font-headline-md text-headline-md mb-3 text-primary">Boorsoks</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-4">Золотистые кусочки жареного теста, символ праздника. Хрустящие снаружи и мягкие внутри.</p>
<span class="material-symbols-outlined text-secondary">bakery_dining</span>
</div>
</div>
<!-- Plov -->
<div class="md:col-span-4 group relative overflow-hidden rounded-3xl shadow-[0_4px_24px_rgba(0,64,82,0.06)] bg-surface-container-lowest">
<img class="w-full h-64 object-cover" data-alt="Kyrgyz Plov in a large cast iron cauldron with dark red carrots, garlic cloves, and steaming rice" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDD5VDU_zfB34CG7M-xbMQIu_JT3cfiyUcM1QtZ_g2WTpKTj9gRCGRwKMPK1C3yJKMRidy1k1pFWu6K_Ux2O2WhaVZx20G5VFYTofAYe6eULEHpsZ-icz8Ssidk2vixxEAAhI2VUqr99ZvzJlH2TbDveMAYzBAX3omqetsFSy8eYeTWgDdv8_9KXjz_qDjWaruCmyTSMMSQgMkjqSa7XpYh0lt00mSPSf_Mtvr9K1llhjkB3VkpFGxNjmF9qsGbosxeBh9yS4juex8"/>
<div class="p-8">
<h2 class="font-headline-md text-headline-md mb-3 text-primary">Plov</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-4">Легендарный узгенский рис, томленый с мясом и ароматной морковью в чугунном казане.</p>
<span class="material-symbols-outlined text-secondary">outdoor_grill</span>
</div>
</div>
<!-- Kymyz -->
<div class="md:col-span-8 group relative overflow-hidden rounded-3xl shadow-[0_4px_24px_rgba(0,64,82,0.06)] bg-surface-container-lowest">
<div class="flex flex-col md:flex-row h-full">
<div class="md:w-1/2 p-10 flex flex-col justify-center order-2 md:order-1">
<span class="text-secondary font-label-sm uppercase mb-4 tracking-widest">Эликсир Гор</span>
<h2 class="font-headline-lg text-headline-lg mb-4 text-primary">Kymyz</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-6">Целебный напиток из кобыльего молока, выдержанный в кожаных бурдюках. Освежающий, слегка газированный вкус с дымным ароматом арчи.</p>
<button class="border-2 border-[#D66853] text-[#D66853] px-6 py-3 rounded-xl font-bold hover:bg-[#D66853] hover:text-white transition-all w-fit">Узнать о пользе</button>
</div>
<div class="md:w-1/2 overflow-hidden order-1 md:order-2">
<img class="w-full h-full object-cover" data-alt="traditional leather vessel for Kymyz being poured into a wooden bowl in a high altitude mountain pasture" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAjWf5ANRFWWN0s5wzRozIy971ryUkoORMq6kMScoXlpmjAQFTtWudrV2-HR1WMv081pRRJtcOInJ38MXebmxe3tMx1ua9gqDFJfZSVEKWvhSEj_dAfw2FqdBUsPtlqTJ0SJ8hx9hn3Sv1cuWdAExelScMREnMGN10tr8Y7HYDs1BEjPt6vrfPuWJNvSGSd291aeO48FXiC5NVcnZDWiXH-MgwJiwVjwMoMerT9sxY8VxkqDlvYosfgBCQRSbToW1i2zXGESqAAhCE"/>
</div>
</div>
</div>
</div>
</section>
<!-- Where to try section -->
<section class="bg-surface-container py-24">
<div class="max-w-7xl mx-auto px-8">
<div class="text-center mb-16">
<h2 class="font-headline-lg text-headline-lg text-primary mb-4">Где Попробовать?</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant">Лучшие места для аутентичного гастрономического опыта</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-12">
<div class="text-center">
<div class="w-20 h-20 bg-primary-container/10 rounded-full flex items-center justify-center mx-auto mb-6">
<span class="material-symbols-outlined text-primary-container text-4xl">home_work</span>
</div>
<h3 class="font-headline-md text-headline-md mb-3">Юрточные Лагеря</h3>
<p class="font-body-md text-body-md text-on-surface-variant">Самый честный вкус — на джайлоо (высокогорных пастбищах). Здесь готовят на открытом огне из свежайших фермерских продуктов.</p>
</div>
<div class="text-center">
<div class="w-20 h-20 bg-primary-container/10 rounded-full flex items-center justify-center mx-auto mb-6">
<span class="material-symbols-outlined text-primary-container text-4xl">storefront</span>
</div>
<h3 class="font-headline-md text-headline-md mb-3">Ошский Базар</h3>
<p class="font-body-md text-body-md text-on-surface-variant">В Бишкеке отправляйтесь на рынки за уличной едой: самсы, свежие лепешки и горячий чай в местных чайханах.</p>
</div>
<div class="text-center">
<div class="w-20 h-20 bg-primary-container/10 rounded-full flex items-center justify-center mx-auto mb-6">
<span class="material-symbols-outlined text-primary-container text-4xl">restaurant</span>
</div>
<h3 class="font-headline-md text-headline-md mb-3">Рестораны Чайхана</h3>
<p class="font-body-md text-body-md text-on-surface-variant">В городах ищите заведения с надписью «Чайхана». Это центры социальной жизни, где Beshbarmak подают по всем канонам.</p>
</div>
</div>
</div>
</section>
<!-- CTA Section -->
<section class="max-w-5xl mx-auto px-8 my-section-gap">
<div class="bg-primary rounded-[40px] p-12 md:p-20 text-center relative overflow-hidden shadow-2xl">
<div class="absolute top-0 right-0 p-8 opacity-10">
<span class="material-symbols-outlined text-9xl">flatware</span>
</div>
<h2 class="font-display-xl text-headline-lg md:text-display-xl text-surface-container-lowest mb-8">Готовы к приключению?</h2>
<p class="font-body-lg text-body-lg text-primary-fixed mb-10 max-w-2xl mx-auto">Забронируйте гастрономический тур и погрузитесь в культуру Кыргызстана через его вкусы.</p>
<div class="flex flex-col md:flex-row gap-4 justify-center">
<button class="bg-[#D66853] text-white px-10 py-4 rounded-full font-bold text-lg hover:scale-105 transition-transform">Забронировать Тур</button>
<button class="bg-white/10 text-white backdrop-blur-sm border border-white/20 px-10 py-4 rounded-full font-bold text-lg hover:bg-white/20 transition-all">Смотреть Меню</button>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-stone-100 dark:bg-stone-950 full-width py-20 border-t-2 border-[#D66853]">
<div class="max-w-7xl mx-auto px-8 grid grid-cols-1 md:grid-cols-3 gap-12">
<div>
<h4 class="text-lg font-bold text-[#005F73] mb-6 font-serif">Kyrgyzstan</h4>
<p class="font-serif text-sm text-stone-600 dark:text-stone-400 leading-relaxed">© 2024 Discover Kyrgyzstan. Handcrafted by Nomads.</p>
</div>
<div class="flex flex-col gap-4">
<a class="font-serif text-sm text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-colors" href="#">Contact Us</a>
<a class="font-serif text-sm text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-colors" href="#">Privacy Policy</a>
</div>
<div class="flex flex-col gap-4">
<a class="font-serif text-sm text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-colors" href="#">Sustainability Pledge</a>
<a class="font-serif text-sm text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-colors" href="#">Media Kit</a>
</div>
</div>
</footer>
<!-- BottomNavBar (Mobile Only) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full z-50 flex justify-around items-center px-4 pb-safe h-20 bg-white/90 backdrop-blur-md dark:bg-stone-950/90 rounded-t-3xl border-t border-stone-100 dark:border-stone-800 shadow-[0_-4px_24px_rgba(0,64,82,0.1)]">
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined">home</span>
<span class="font-serif text-[10px] font-medium">Home</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined">waves</span>
<span class="font-serif text-[10px] font-medium">Lakes</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined">temple_buddhist</span>
<span class="font-serif text-[10px] font-medium">Culture</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined">terrain</span>
<span class="font-serif text-[10px] font-medium">Nature</span>
</div>
<div class="flex flex-col items-center justify-center bg-teal-50 dark:bg-teal-900/30 text-[#005F73] dark:text-teal-200 rounded-2xl px-4 py-1">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">restaurant</span>
<span class="font-serif text-[10px] font-medium">Cuisine</span>
</div>
</nav>
</body></html><!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Nature and Trekking - Kyrgyzstan</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:wght@400;600;700&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "primary-container": "#005f73",
                        "on-surface-variant": "#3f484c",
                        "on-surface": "#191c1d",
                        "on-primary-fixed": "#001f27",
                        "secondary-fixed-dim": "#ffb4ab",
                        "tertiary-container": "#7e492b",
                        "outline": "#6f797c",
                        "error": "#ba1a1a",
                        "on-error-container": "#93000a",
                        "on-secondary-container": "#fffbff",
                        "on-primary-container": "#91d7ee",
                        "primary-fixed-dim": "#8bd1e8",
                        "inverse-primary": "#8bd1e8",
                        "background": "#f8f9fa",
                        "error-container": "#ffdad6",
                        "on-primary-fixed-variant": "#004e5f",
                        "surface-container-lowest": "#ffffff",
                        "surface-container": "#edeeef",
                        "on-secondary-fixed": "#410002",
                        "on-error": "#ffffff",
                        "surface-variant": "#e1e3e4",
                        "secondary-container": "#de2e2c",
                        "on-tertiary-fixed": "#331100",
                        "outline-variant": "#bfc8cc",
                        "on-secondary-fixed-variant": "#93000d",
                        "on-secondary": "#ffffff",
                        "secondary": "#b90c17",
                        "on-background": "#191c1d",
                        "surface-tint": "#13677b",
                        "surface-container-high": "#e7e8e9",
                        "on-tertiary": "#ffffff",
                        "on-primary": "#ffffff",
                        "secondary-fixed": "#ffdad6",
                        "tertiary-fixed": "#ffdbca",
                        "surface": "#f8f9fa",
                        "on-tertiary-container": "#ffbe9c",
                        "inverse-surface": "#2e3132",
                        "primary-fixed": "#b2ebff",
                        "tertiary-fixed-dim": "#feb691",
                        "surface-bright": "#f8f9fa",
                        "tertiary": "#623317",
                        "surface-container-low": "#f3f4f5",
                        "primary": "#004655",
                        "surface-container-highest": "#e1e3e4",
                        "on-tertiary-fixed-variant": "#6b3a1d",
                        "surface-dim": "#d9dadb",
                        "inverse-on-surface": "#f0f1f2"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "gutter": "24px",
                        "margin-desktop": "40px",
                        "unit": "8px",
                        "margin-mobile": "16px",
                        "container-max": "1280px",
                        "section-gap": "120px"
                    },
                    "fontFamily": {
                        "body-md": ["Manrope"],
                        "label-sm": ["Manrope"],
                        "headline-lg": ["Noto Serif"],
                        "display-xl": ["Noto Serif"],
                        "body-lg": ["Manrope"],
                        "headline-md": ["Noto Serif"]
                    },
                    "fontSize": {
                        "body-md": ["16px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "label-sm": ["14px", {"lineHeight": "1.0", "letterSpacing": "0.05em", "fontWeight": "600"}],
                        "headline-lg": ["40px", {"lineHeight": "1.2", "fontWeight": "600"}],
                        "display-xl": ["64px", {"lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                        "body-lg": ["18px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "headline-md": ["28px", {"lineHeight": "1.3", "fontWeight": "600"}]
                    }
                },
            },
        }
    </script>
<style>
        body { font-family: 'Manrope', sans-serif; }
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background text-on-surface">
<!-- TopAppBar -->
<header class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-6 h-16 bg-[#F8F9FA] dark:bg-stone-950 border-b border-stone-200 dark:border-stone-800 shadow-[0_4px_20px_-2px_rgba(0,64,82,0.08)]">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#005F73] dark:text-teal-400 cursor-pointer">menu</span>
<span class="text-2xl font-bold tracking-widest uppercase text-[#005F73] dark:text-teal-500 font-serif">Kyrgyzstan</span>
</div>
<nav class="hidden md:flex gap-8">
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Home</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Lakes</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Culture</a>
<a class="text-[#005F73] font-bold border-b-2 border-[#D66853] font-serif" href="#">Nature</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Cuisine</a>
</nav>
<div class="flex items-center gap-2 text-[#005F73] dark:text-teal-400 cursor-pointer">
<span class="material-symbols-outlined">language</span>
<span class="font-label-sm text-label-sm">RU</span>
</div>
</header>
<main class="pt-16">
<!-- Hero Section -->
<section class="relative h-[751px] flex items-center justify-center overflow-hidden">
<img alt="Kyrgyzstan Nature" class="absolute inset-0 w-full h-full object-cover" data-alt="Epic panoramic view of snow-capped Kyrgyzstan mountains with a winding turquoise river valley at sunrise, soft golden lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCPHOlPEK57ZFV8fLsYN300ecsXM9ToH0WvcoN18KBbVego3xjH_jMB_-LN1WVKO-WSVKlMKa8UHdj3W4Vodvwo4wCC0dpYMkChnaSfqV0HC-ea4uc-ysmV4z8PbHEUd21khNepGlBsG8gTVFOPbbc-TWI34Y5xunbkwQ7_pcVEG8XOAy4RoLOWMoop32R0yMKsu9DJfnJfJiFURQuiIQ9ThWDuERyjHniHM92MLV0jiFt45QOx3ug16yTdSFmaEHg6pLc5UOzoqNs"/>
<div class="absolute inset-0 bg-gradient-to-b from-black/40 via-transparent to-background"></div>
<div class="relative z-10 text-center px-6 max-w-4xl">
<h1 class="font-display-xl text-display-xl text-white mb-6 drop-shadow-lg">Нетронутая Природа</h1>
<p class="font-body-lg text-body-lg text-white/90 max-w-2xl mx-auto drop-shadow-md">Откройте для себя величие Тянь-Шаня, где горы встречаются с небом, а время замирает в объятиях дикой природы.</p>
<div class="mt-10 flex flex-wrap justify-center gap-4">
<button class="bg-primary-container text-white px-8 py-4 rounded-xl font-label-sm text-label-sm hover:translate-y-[-2px] transition-transform">Исследовать маршруты</button>
<button class="border border-white text-white px-8 py-4 rounded-xl font-label-sm text-label-sm backdrop-blur-sm hover:bg-white/10 transition-all">Забронировать гида</button>
</div>
</div>
</section>
<!-- Featured Destinations (Bento Grid) -->
<section class="max-w-7xl mx-auto px-6 py-[120px]">
<div class="text-center mb-16">
<span class="text-[#D66853] font-label-sm tracking-widest uppercase mb-2 block">Места Силы</span>
<h2 class="font-headline-lg text-headline-lg text-primary">Главные Жемчужины</h2>
</div>
<div class="grid grid-cols-1 md:grid-cols-12 gap-8 h-[800px] md:h-[600px]">
<!-- Ala-Archa -->
<div class="md:col-span-8 relative rounded-3xl overflow-hidden shadow-xl group">
<img alt="Ala-Archa" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="Dramatic sharp peaks of Ala-Archa gorge with pine trees and alpine meadows under a clear blue sky" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC7h6G3bJv902UJhsV46rR6-c5x4wXF3BhU_xclXDzLwYbM9TGgj1q1ofhh34VuXEnhxOxSIyVIYfwOgrYxOSAEEdw3PZss0GUxxXVnCyYqR8VrN5WmLlWwAM3dYnz3fQqzBaKpNRX8-mK6-W3LjF3d7_dDe6JCvtBiqSOcK-alQFJVud5KNdQWpEYf0Koa1APwM1Qyv319LnBdWlBM09TeTJ3p1nISJmNy7JoG4DOqMpq7Kslg-TzRmdbHne_7pqTIP-DJbJU-NRs"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent"></div>
<div class="absolute bottom-0 left-0 p-8">
<h3 class="font-headline-md text-headline-md text-white mb-2">Ущелье Ала-Арча</h3>
<p class="font-body-md text-white/80 max-w-md">Альпийский национальный парк всего в 40 км от Бишкека с ледниками и водопадами.</p>
</div>
</div>
<!-- Jeti-Oguz -->
<div class="md:col-span-4 relative rounded-3xl overflow-hidden shadow-xl group">
<img alt="Jeti-Oguz" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="Iconic red rock formations of Jeti-Oguz Seven Bulls at sunset with vibrant orange and red hues" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBszioENd-7FwsAiD7DDaETsxeMkja5wWQZPQ0Ye9YdjOlYe8zG65ZkIkbHxWcroQK0D5YcEMQg0Qr2cEimO5teR8-wigmpiPLK3ytkedt68Ho3xRmVNR0PRrA7mPj1AucstSBYQDzVRGT89N0-FNKK7QjNLGA_3p9V5mr_QoTwXo3OBU39jcYWAoscKtIBM5wTHthbyEZsFFSdsDJk_DdszL7Oe_ABf-zdDIarzO2rDSWFdZIBiuyC_-KCvBJCxpByNUAz_KgSdhY"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent"></div>
<div class="absolute bottom-0 left-0 p-8">
<h3 class="font-headline-md text-headline-md text-white mb-2">Джети-Огуз</h3>
<p class="font-body-md text-white/80">Знаменитые скалы «Семь Быков», окрашенные в огненно-красный цвет закатным солнцем.</p>
</div>
</div>
</div>
</section>
<!-- Cultural Divider -->
<div class="max-w-4xl mx-auto flex items-center justify-center gap-8 py-12">
<div class="h-[2px] flex-1 bg-stone-200"></div>
<div class="w-12 h-12 flex items-center justify-center text-[#D66853]">
<span class="material-symbols-outlined text-4xl" style="font-variation-settings: 'FILL' 1;">circles</span>
</div>
<div class="h-[2px] flex-1 bg-stone-200"></div>
</div>
<!-- Hiking Routes -->
<section class="bg-surface-container-low py-[120px]">
<div class="max-w-7xl mx-auto px-6">
<div class="flex flex-col md:flex-row justify-between items-end mb-16 gap-6">
<div class="max-w-xl">
<span class="text-[#D66853] font-label-sm tracking-widest uppercase mb-2 block">Активный Отдых</span>
<h2 class="font-headline-lg text-headline-lg text-primary">Популярные Маршруты</h2>
<p class="font-body-md text-on-surface-variant mt-4">От легких прогулок до категорийных восхождений — каждый найдет свой путь в горах Киргизии.</p>
</div>
<a class="text-primary-container font-label-sm flex items-center gap-2 hover:underline" href="#">Смотреть все маршруты <span class="material-symbols-outlined">arrow_forward</span></a>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<!-- Route 1 -->
<div class="bg-white rounded-[32px] overflow-hidden shadow-sm hover:shadow-xl transition-shadow border border-stone-100">
<img alt="Hiking Route" class="h-64 w-full object-cover" data-alt="A lone hiker on a rocky ridge looking over a vast mountain range with green valleys below" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDbfhQS-L3AzenFIl6WEJfSn0brW6bsImI1vgWAWaqsSnzD5Prd5z0IvAclRbncewvT04PaGcCZOKMqK4fGLjjUx6xr6dv7Zy9KCSnwL7j9vnw9jowUrFXN4t20yMWoCyHdc_0vcXC0v1lFawdp_g_QMwHX3TpGO9EchxMZGkx4fcwHvYBeBXDXLT6F77mnhyZVlEGXtgX34TzYTQh1VbM7XKR9SlScUpVdYcaICpWvul5xOPT3H7JFSSbk1WwMpREt8sLhh0KHfCM"/>
<div class="p-8">
<div class="flex gap-2 mb-4">
<span class="bg-teal-50 text-primary-container px-3 py-1 rounded-full text-[12px] font-bold uppercase tracking-wider">Сложный</span>
<span class="bg-stone-100 text-on-surface-variant px-3 py-1 rounded-full text-[12px] font-bold uppercase tracking-wider">3 Дня</span>
</div>
<h4 class="font-headline-md text-headline-md text-primary mb-3">Хижина Рацека</h4>
<p class="font-body-md text-on-surface-variant mb-6">Классический маршрут в Ала-Арче, ведущий к базе альпинистов на высоте 3300м.</p>
<div class="flex items-center justify-between pt-6 border-t border-stone-100">
<span class="text-on-surface-variant flex items-center gap-1"><span class="material-symbols-outlined text-sm">terrain</span> 3300м</span>
<button class="text-primary font-bold">Детали</button>
</div>
</div>
</div>
<!-- Route 2 -->
<div class="bg-white rounded-[32px] overflow-hidden shadow-sm hover:shadow-xl transition-shadow border border-stone-100">
<img alt="Eco Tour" class="h-64 w-full object-cover" data-alt="Sunlight filtering through a dense pine forest in the mountains, misty atmosphere" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDyFUoKyo0MPVE8x_9IRjSbhxkSUTfsa5cURUDy80eoX6LlmYzL-68A7aDPnrf_6LLJwGzgeWPvviqSDDC5UTm84j_xXmmNuvZHeP8uJzISAdl3_WdancohmEtUnfKu3iYc00QojoGvGOpMz0w_qOgwsVE7RwwoSCE24bxeVIB4rwVWL8xHuatd6ErdAaCvc7kiJPsjB-dELvC2oP_8cuHYjGqOkqnfGgfvGKdDRvZC2kSimpgw4edBid8gagXqvfGPk2Agm4sEJ7g"/>
<div class="p-8">
<div class="flex gap-2 mb-4">
<span class="bg-stone-100 text-on-surface-variant px-3 py-1 rounded-full text-[12px] font-bold uppercase tracking-wider">Легкий</span>
<span class="bg-stone-100 text-on-surface-variant px-3 py-1 rounded-full text-[12px] font-bold uppercase tracking-wider">1 День</span>
</div>
<h4 class="font-headline-md text-headline-md text-primary mb-3">Водопад Ак-Сай</h4>
<p class="font-body-md text-on-surface-variant mb-6">Живописная тропа через еловые леса к одному из красивейших водопадов ущелья.</p>
<div class="flex items-center justify-between pt-6 border-t border-stone-100">
<span class="text-on-surface-variant flex items-center gap-1"><span class="material-symbols-outlined text-sm">water_drop</span> 20м</span>
<button class="text-primary font-bold">Детали</button>
</div>
</div>
</div>
<!-- Route 3 -->
<div class="bg-white rounded-[32px] overflow-hidden shadow-sm hover:shadow-xl transition-shadow border border-stone-100">
<img alt="Trekking" class="h-64 w-full object-cover" data-alt="Stunning clear blue alpine lake surrounded by steep snowy mountains, tranquil reflection" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCMFyRg1cvCebfaTX1AlyrNfvPQPvWtJWgLugN3CFr7kj6hlaNEaOSv-cpJAUwWjj6Vu6X5qNS3-LXvy0Py-1ffj5YNDY1eP6eb4HwKACrM_U1sXuyNmgjY-X1reK2h7PgD2qQ7KOvq2N_eXroKTxSnxSMVhA0yh-r5VijodG7Ks1fWQxzkcciLO0u23YISCTcrEJbS6eqyyfWsYM3GgrMK41PP75eJ3ZDTwGlChOJhV_smwlkjasnnfr7d0k6ExEErC2dJa4c5SRI"/>
<div class="p-8">
<div class="flex gap-2 mb-4">
<span class="bg-orange-50 text-orange-800 px-3 py-1 rounded-full text-[12px] font-bold uppercase tracking-wider">Средний</span>
<span class="bg-stone-100 text-on-surface-variant px-3 py-1 rounded-full text-[12px] font-bold uppercase tracking-wider">2 Дня</span>
</div>
<h4 class="font-headline-md text-headline-md text-primary mb-3">Озеро Ала-Куль</h4>
<p class="font-body-md text-on-surface-variant mb-6">Высокогорное бирюзовое озеро, спрятанное среди ледников на высоте 3500м.</p>
<div class="flex items-center justify-between pt-6 border-t border-stone-100">
<span class="text-on-surface-variant flex items-center gap-1"><span class="material-symbols-outlined text-sm">waves</span> 3500м</span>
<button class="text-primary font-bold">Детали</button>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Eco-Tours Call to Action -->
<section class="max-w-7xl mx-auto px-6 py-[120px]">
<div class="bg-primary text-white rounded-[40px] overflow-hidden flex flex-col md:flex-row items-center">
<div class="p-12 md:p-20 md:w-1/2">
<h2 class="font-headline-lg text-headline-lg mb-6">Эко-туры в сердце природы</h2>
<p class="font-body-lg text-white/80 mb-8 leading-relaxed">Мы придерживаемся принципов устойчивого туризма, сохраняя чистоту наших гор. Присоединяйтесь к нашим экспедициям с ночевкой в юртах и традиционной кухней.</p>
<ul class="space-y-4 mb-10">
<li class="flex items-center gap-3">
<span class="material-symbols-outlined text-teal-400">check_circle</span>
<span class="font-body-md">Сертифицированные горные гиды</span>
</li>
<li class="flex items-center gap-3">
<span class="material-symbols-outlined text-teal-400">check_circle</span>
<span class="font-body-md">Поддержка местных сообществ</span>
</li>
<li class="flex items-center gap-3">
<span class="material-symbols-outlined text-teal-400">check_circle</span>
<span class="font-body-md">Снаряжение премиум класса включено</span>
</li>
</ul>
<button class="bg-white text-primary px-10 py-5 rounded-2xl font-bold hover:scale-105 transition-transform shadow-lg">Подобрать эко-тур</button>
</div>
<div class="md:w-1/2 h-[400px] md:h-full relative">
<img alt="Eco Yurt Stay" class="absolute inset-0 w-full h-full object-cover" data-alt="A group of colorful traditional Kyrgyz yurts in a wide green valley surrounded by snowy mountains" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB4jNzunpFgBCp1Y4jH7xyakZ_sUV4-l4gfnwP478BsLw1wysuP3flh0-9xwx0IVWBoQZVL1BSLrK38ZuOoTf7oV_346lazbS-D_tB15xxP_MGyKg3o_3dPDuZi1d5DrNNW6vvozpmVopxXDlvUNI2I95ZUvlHdIwngbXGdbmo2Eq5i7xo4LJj2ToVWPYMe2LbMEnswbd5yg36vNRDB2F5zwhRBekkBJX6iVxr8kE6pyHQ1UevT-EXSw8FJ8vXxNtBKYKxEghWeQGc"/>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-stone-100 dark:bg-stone-950 full-width py-20 border-t-2 border-[#D66853]">
<div class="max-w-7xl mx-auto px-8 grid grid-cols-1 md:grid-cols-3 gap-12">
<div class="flex flex-col gap-6">
<span class="text-lg font-bold text-[#005F73] font-serif uppercase tracking-widest">Kyrgyzstan</span>
<p class="font-serif text-sm text-stone-600 dark:text-stone-400 max-w-xs">Исследуйте дикую природу Средней Азии с комфортом и уважением к традициям.</p>
<div class="flex gap-4">
<span class="material-symbols-outlined cursor-pointer hover:text-[#005F73]">social_leaderboard</span>
<span class="material-symbols-outlined cursor-pointer hover:text-[#005F73]">public</span>
<span class="material-symbols-outlined cursor-pointer hover:text-[#005F73]">camera</span>
</div>
</div>
<div class="flex flex-col gap-4">
<h5 class="font-bold text-primary mb-2">Навигация</h5>
<a class="text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-colors font-serif text-sm" href="#">Contact Us</a>
<a class="text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-colors font-serif text-sm" href="#">Privacy Policy</a>
<a class="text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-colors font-serif text-sm" href="#">Sustainability Pledge</a>
<a class="text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-colors font-serif text-sm" href="#">Media Kit</a>
</div>
<div class="flex flex-col gap-6">
<h5 class="font-bold text-primary">Подпишитесь на новости</h5>
<div class="flex bg-white dark:bg-stone-900 rounded-xl overflow-hidden border border-stone-200 dark:border-stone-800">
<input class="bg-transparent border-none focus:ring-0 px-4 py-3 flex-1 text-sm" placeholder="Ваш Email" type="email"/>
<button class="bg-[#005F73] text-white px-6 py-3 material-symbols-outlined">send</button>
</div>
<p class="text-[10px] text-stone-500 font-serif uppercase tracking-tighter">© 2024 Discover Kyrgyzstan. Handcrafted by Nomads.</p>
</div>
</div>
</footer>
<!-- BottomNavBar (Mobile Only) -->
<div class="md:hidden fixed bottom-0 left-0 w-full z-50 flex justify-around items-center px-4 pb-safe h-20 bg-white/90 backdrop-blur-md dark:bg-stone-950/90 border-t border-stone-100 dark:border-stone-800 shadow-[0_-4px_24px_rgba(0,64,82,0.1)]">
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined">home</span>
<span class="font-serif text-[10px] font-medium">Home</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined">waves</span>
<span class="font-serif text-[10px] font-medium">Lakes</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined">temple_buddhist</span>
<span class="font-serif text-[10px] font-medium">Culture</span>
</div>
<div class="flex flex-col items-center justify-center bg-teal-50 dark:bg-teal-900/30 text-[#005F73] dark:text-teal-200 rounded-2xl px-4 py-1 transition-transform">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">terrain</span>
<span class="font-serif text-[10px] font-medium">Nature</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined">restaurant</span>
<span class="font-serif text-[10px] font-medium">Cuisine</span>
</div>
</div>
</body></html><!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Kyrgyzstan - Культура и Традиции</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:wght@400;600;700&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "primary-container": "#005f73",
                    "on-surface-variant": "#3f484c",
                    "on-surface": "#191c1d",
                    "on-primary-fixed": "#001f27",
                    "secondary-fixed-dim": "#ffb4ab",
                    "tertiary-container": "#7e492b",
                    "outline": "#6f797c",
                    "error": "#ba1a1a",
                    "on-error-container": "#93000a",
                    "on-secondary-container": "#fffbff",
                    "on-primary-container": "#91d7ee",
                    "primary-fixed-dim": "#8bd1e8",
                    "inverse-primary": "#8bd1e8",
                    "background": "#f8f9fa",
                    "error-container": "#ffdad6",
                    "on-primary-fixed-variant": "#004e5f",
                    "surface-container-lowest": "#ffffff",
                    "surface-container": "#edeeef",
                    "on-secondary-fixed": "#410002",
                    "on-error": "#ffffff",
                    "surface-variant": "#e1e3e4",
                    "secondary-container": "#de2e2c",
                    "on-tertiary-fixed": "#331100",
                    "outline-variant": "#bfc8cc",
                    "on-secondary-fixed-variant": "#93000d",
                    "on-secondary": "#ffffff",
                    "secondary": "#b90c17",
                    "on-background": "#191c1d",
                    "surface-tint": "#13677b",
                    "surface-container-high": "#e7e8e9",
                    "on-tertiary": "#ffffff",
                    "on-primary": "#ffffff",
                    "secondary-fixed": "#ffdad6",
                    "tertiary-fixed": "#ffdbca",
                    "surface": "#f8f9fa",
                    "on-tertiary-container": "#ffbe9c",
                    "inverse-surface": "#2e3132",
                    "primary-fixed": "#b2ebff",
                    "tertiary-fixed-dim": "#feb691",
                    "surface-bright": "#f8f9fa",
                    "tertiary": "#623317",
                    "surface-container-low": "#f3f4f5",
                    "primary": "#004655",
                    "surface-container-highest": "#e1e3e4",
                    "on-tertiary-fixed-variant": "#6b3a1d",
                    "surface-dim": "#d9dadb",
                    "inverse-on-surface": "#f0f1f2"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "full": "9999px"
            },
            "spacing": {
                    "gutter": "24px",
                    "margin-desktop": "40px",
                    "unit": "8px",
                    "margin-mobile": "16px",
                    "container-max": "1280px",
                    "section-gap": "120px"
            },
            "fontFamily": {
                    "body-md": ["Manrope"],
                    "label-sm": ["Manrope"],
                    "headline-lg": ["Noto Serif"],
                    "display-xl": ["Noto Serif"],
                    "body-lg": ["Manrope"],
                    "headline-md": ["Noto Serif"]
            },
            "fontSize": {
                    "body-md": ["16px", {"lineHeight": "1.6", "fontWeight": "400"}],
                    "label-sm": ["14px", {"lineHeight": "1.0", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "headline-lg": ["40px", {"lineHeight": "1.2", "fontWeight": "600"}],
                    "display-xl": ["64px", {"lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                    "body-lg": ["18px", {"lineHeight": "1.6", "fontWeight": "400"}],
                    "headline-md": ["28px", {"lineHeight": "1.3", "fontWeight": "600"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .oimok-pattern {
            background-image: radial-gradient(#D66853 0.5px, transparent 0.5px);
            background-size: 24px 24px;
            opacity: 0.1;
        }
        .text-shadow-hero {
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background text-on-surface font-body-md overflow-x-hidden">
<!-- TopAppBar -->
<nav class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-6 h-16 bg-[#F8F9FA] dark:bg-stone-950 shadow-[0_4px_20px_-2px_rgba(0,64,82,0.08)] border-b border-stone-200 dark:border-stone-800">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#005F73] dark:text-teal-400 cursor-pointer" data-icon="menu">menu</span>
<span class="text-2xl font-bold tracking-widest uppercase text-[#005F73] dark:text-teal-500 font-serif">Kyrgyzstan</span>
</div>
<div class="hidden md:flex items-center gap-8">
<a class="font-serif text-teal-900 dark:text-stone-100 text-[#005F73] font-bold border-b-2 border-[#D66853] transition-all" href="#">Культура</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Природа</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Гид</a>
</div>
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#005F73] dark:text-teal-400 cursor-pointer" data-icon="language">language</span>
</div>
</nav>
<!-- Hero Section -->
<header class="relative h-[795px] flex items-center justify-center overflow-hidden pt-16">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover" data-alt="majestic landscape of kyrgyz mountains at sunset with a lone traditional yurt in the foreground and warm golden lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCOERyARkrsV7bRNkgw-1RvqsStSqIsg1VgskBiNw3xhVhJT61IwdQJEG2EsVtFkNq6W-NbNR2HpJ_Koh0cgq4dukfAlRCJ0R0Wtd1nWE4vMiIj5Xlvv_glY4ZSc6gVUGVsbzdDlKBjk8nJ7ziTbXpWyT-m8Zcr13oqBQu2RoRDLjQIu9Jsr3JZf4IHnp-GdTjB1sEiCDk6lRqTPy1XNGAnyYkEqYO2G0bZRJgp7w-Bw486DajynMrzhei9yLM5ar32J_98DwXNJ4o"/>
<div class="absolute inset-0 bg-gradient-to-b from-primary/30 to-black/60"></div>
</div>
<div class="relative z-10 text-center px-6">
<h1 class="font-display-xl text-display-xl text-surface-container-lowest text-shadow-hero mb-6">Душа Кочевника</h1>
<p class="font-body-lg text-body-lg text-surface-container-lowest max-w-2xl mx-auto opacity-90">Откройте для себя многовековое наследие, где гостеприимство священно, а горы хранят мелодии предков.</p>
</div>
</header>
<main class="max-w-container-max mx-auto px-6 py-section-gap space-y-section-gap">
<!-- Nomadic Hospitality (Focus Section) -->
<section class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
<div class="space-y-8">
<div class="inline-flex items-center gap-2 px-4 py-2 bg-tertiary-container/10 rounded-full text-tertiary">
<span class="material-symbols-outlined text-sm" data-icon="heart_plus" data-weight="fill">heart_plus</span>
<span class="font-label-sm text-label-sm uppercase tracking-wider">Наследие</span>
</div>
<h2 class="font-headline-lg text-headline-lg text-primary">Кочевое Гостеприимство</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant leading-relaxed">
                    В кыргызской культуре гость — это благословение. «Мейман — бул ырыс» (Гость приносит счастье). Путника всегда встретят с горячим чаем, свежими боорсоками и лучшими угощениями, даже если он зашел в юрту случайно.
                </p>
<div class="grid grid-cols-2 gap-4">
<div class="p-6 bg-surface-container-low rounded-xl border-l-4 border-secondary">
<h4 class="font-bold text-primary mb-2">Чайная церемония</h4>
<p class="text-sm text-on-surface-variant">Каждый прием начинается с ароматного чая в пиале.</p>
</div>
<div class="p-6 bg-surface-container-low rounded-xl border-l-4 border-secondary">
<h4 class="font-bold text-primary mb-2">Дастархан</h4>
<p class="text-sm text-on-surface-variant">Щедрый стол, символизирующий изобилие и мир.</p>
</div>
</div>
</div>
<div class="relative">
<div class="absolute -top-4 -left-4 w-24 h-24 oimok-pattern"></div>
<img class="rounded-3xl shadow-2xl relative z-10 w-full aspect-[4/5] object-cover" data-alt="close-up of traditional kyrgyz table spread with boorsoks, tea, and colorful textiles inside a warmly lit yurt" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAvyplzSA3vG0jFHWItDc1G5UYqlsjyZd6RQy7Y0msfgJp5iGzE3j5Cmn539kC0iKdS2LpINEjUoNJh3uX3UdRZus6YrSPKQY_JVIf_F5W3-rkCPp4jNZcxQHt9lpP3wCVPw6johcEOTMD3UvtQCR9NEs_CKYgFsg_x3UUpik7fDxrabryLV4HDpkKz-_CgqjkZpYrHJ9uS0HQbHwdZxy8njzevW-KT8UMJCMwImpfOhKX5lXRn0dtL44L7dJ4oth5KsooF1yFTYlM"/>
<div class="absolute -bottom-6 -right-6 bg-secondary text-on-secondary p-8 rounded-2xl hidden md:block">
<p class="font-serif italic text-xl">«Гость — посланник Бога»</p>
</div>
</div>
</section>
<!-- Cultural Divider -->
<div class="flex items-center justify-center gap-8 py-12">
<div class="h-px flex-1 bg-stone-300"></div>
<div class="relative w-12 h-12 flex items-center justify-center border-2 border-secondary rounded-full">
<span class="material-symbols-outlined text-secondary" data-icon="brightness_low" data-weight="fill">brightness_low</span>
</div>
<div class="h-px flex-1 bg-stone-300"></div>
</div>
<!-- Bento Grid: Sports & Music -->
<section class="grid grid-cols-1 md:grid-cols-3 gap-8">
<!-- Kok-Boru -->
<div class="md:col-span-2 group relative overflow-hidden rounded-3xl bg-primary text-white p-12 flex flex-col justify-end min-h-[500px]">
<img class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" data-alt="dramatic action shot of men on horses playing kok-boru in a mountain arena with dust clouds and intense competition" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDOwS_cL33eL_RsLVK71MsvOyOXycBzv5CnMz3gpvJGjGWFmsrkhYl0O5T4CRKor2zeeTmZHAJ99umGc0bCjE8OmlMCN7Vlt2X3TsR0wk3gCH_nZ2beFfwl8sV_i1FUR6R7Dm-ORr-njDkWeRShedH7Ytg_i1mndBnSzmgJAQBxnbTyNT6qn0xBFuZADvP9-VtLTdXQLQqY_92Ci5MEta-wr1vNcSoaxuSfxofQEYlFB_YwzYS8M6R9fe2EjstJt96xsJvqan7fq04"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent"></div>
<div class="relative z-10 space-y-4">
<h3 class="font-headline-lg text-headline-lg">Көк-Бөрү: Игра Смелых</h3>
<p class="font-body-md text-body-md opacity-90 max-w-xl">Древнее конно-спортивное состязание, демонстрирующее силу, ловкость и дух наездников.</p>
<button class="bg-surface-container-lowest text-primary px-6 py-3 rounded-full font-label-sm uppercase tracking-widest hover:bg-secondary-fixed transition-colors">Смотреть правила</button>
</div>
</div>
<!-- Music & Komuz -->
<div class="bg-surface-container-highest rounded-3xl p-8 flex flex-col items-center text-center space-y-6">
<div class="w-20 h-20 bg-primary-container/20 rounded-full flex items-center justify-center">
<span class="material-symbols-outlined text-primary text-4xl" data-icon="music_note">music_note</span>
</div>
<h3 class="font-headline-md text-headline-md text-primary">Музыка и Комуз</h3>
<img class="rounded-2xl w-full h-48 object-cover shadow-lg" data-alt="close-up of a wooden komuz instrument with intricate carvings being played by hands in traditional clothing" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCbmoBslkhOfGng09Ska2dDOoOvYwYmEQNvBtX-OA6YT3bo-YdQc2sfpvKf7LhtecRlGiXs7BCwRmRpxlC0h6jzL8yB6Bz0LcIZANCxqlqlgzzyLwRnWFik_d9XzKog4_Zz6KsoDrLMr2umC4usq5Fy9-5YTC04hgCJJ5cV1PnqEGKvimhLZ1HIyBpGw2emsI3YM0j_F43qI8F5CtXy2OUex0dREidZbh1_8FLdGdj6IfSjc-egdytuZb5yDLxY65HO0n8Elc8ZXQQ"/>
<p class="font-body-md text-body-md text-on-surface-variant">Комуз — душа народа. Этот трехструнный инструмент способен передать шум ветра и топот копыт.</p>
<div class="flex gap-2">
<span class="px-3 py-1 bg-tertiary/10 text-tertiary rounded-full text-xs font-bold">Фольклор</span>
<span class="px-3 py-1 bg-tertiary/10 text-tertiary rounded-full text-xs font-bold">Эпос Манас</span>
</div>
</div>
</section>
<!-- Yurt Making (Artisan Section) -->
<section class="bg-surface-container-low rounded-[40px] p-8 md:p-20 overflow-hidden relative">
<div class="absolute top-0 right-0 w-1/3 h-full oimok-pattern opacity-5"></div>
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center relative z-10">
<div class="order-2 lg:order-1">
<img class="rounded-3xl shadow-xl border-8 border-white" data-alt="artisans assembling the wooden lattice frame of a yurt against a clear blue mountain sky with traditional felt materials" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAVSSQ4LJOb0fKf0IlkvJ67aLfDKh_7DMIOChm0b891ovRv3CzVhh0s1EEIWa8VkXCT9vU7wg8-ct6enZAoNYH3ZpKLgU6mfuJ7CG0O4NwYXyIJIyYV_QeAGQZUrG1DO3MpivE9Q_WBjwgjsfO9e00DgdywriS6CGI6IMJnCd6YJb5wWswh3ie1noE6gD0BL3liMIA6J9JUkdhiCL9cLYzp1CNrfh6fzvKPWKpc4UtLmmVkrICve4edcCJRgCbrVGQEQVnxX5Az-DM"/>
</div>
<div class="order-1 lg:order-2 space-y-6">
<h2 class="font-headline-lg text-headline-lg text-primary">Искусство возведения Юрты</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant">
                        Юрта — это не просто дом, это модель вселенной. Изготовленная без единого гвоздя из ивы и войлока, она остается идеальным жилищем для кочевого образа жизни.
                    </p>
<ul class="space-y-4">
<li class="flex items-start gap-3">
<span class="material-symbols-outlined text-secondary" data-icon="check_circle">check_circle</span>
<span class="font-body-md"><strong>Тюндюк:</strong> Деревянный обод купола, символ единства семьи.</span>
</li>
<li class="flex items-start gap-3">
<span class="material-symbols-outlined text-secondary" data-icon="check_circle">check_circle</span>
<span class="font-body-md"><strong>Кереге:</strong> Раздвижные решетчатые стены из гибкой ивы.</span>
</li>
<li class="flex items-start gap-3">
<span class="material-symbols-outlined text-secondary" data-icon="check_circle">check_circle</span>
<span class="font-body-md"><strong>Шырдак:</strong> Традиционные войлочные ковры ручной работы.</span>
</li>
</ul>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-stone-100 dark:bg-stone-950 full-width py-20 border-t-2 border-[#D66853]">
<div class="max-w-7xl mx-auto px-8 grid grid-cols-1 md:grid-cols-3 gap-12">
<div class="space-y-6">
<span class="text-lg font-bold text-[#005F73]">Discover Kyrgyzstan</span>
<p class="font-serif text-sm text-stone-600 dark:text-stone-400">Сохраняя традиции, вдохновляя будущее. Путешествие в сердце Средней Азии.</p>
</div>
<div class="flex flex-col gap-4">
<span class="font-bold text-primary uppercase text-xs tracking-widest">Ссылки</span>
<a class="font-serif text-sm text-stone-600 dark:text-stone-400 hover:text-[#005F73]" href="#">Sustainability Pledge</a>
<a class="font-serif text-sm text-stone-600 dark:text-stone-400 hover:text-[#005F73]" href="#">Privacy Policy</a>
<a class="font-serif text-sm text-stone-600 dark:text-stone-400 hover:text-[#005F73]" href="#">Contact Us</a>
</div>
<div class="space-y-6">
<span class="font-bold text-primary uppercase text-xs tracking-widest">Следите за нами</span>
<div class="flex gap-4">
<div class="w-10 h-10 rounded-full border border-stone-300 flex items-center justify-center text-[#005F73] hover:bg-teal-50 transition-colors cursor-pointer">
<span class="material-symbols-outlined" data-icon="public">public</span>
</div>
</div>
<p class="font-serif text-sm text-stone-500">© 2024 Discover Kyrgyzstan. Handcrafted by Nomads.</p>
</div>
</div>
</footer>
<!-- BottomNavBar (Mobile Only) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full z-50 flex justify-around items-center px-4 pb-safe h-20 bg-white/90 backdrop-blur-md dark:bg-stone-950/90 rounded-t-3xl border-t border-stone-100 dark:border-stone-800 shadow-[0_-4px_24px_rgba(0,64,82,0.1)]">
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined" data-icon="home">home</span>
<span class="font-serif text-[10px] font-medium">Home</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined" data-icon="waves">waves</span>
<span class="font-serif text-[10px] font-medium">Lakes</span>
</div>
<div class="flex flex-col items-center justify-center bg-teal-50 dark:bg-teal-900/30 text-[#005F73] dark:text-teal-200 rounded-2xl px-4 py-1 Active: translate-y-[-2px] transition-transform">
<span class="material-symbols-outlined" data-icon="temple_buddhist">temple_buddhist</span>
<span class="font-serif text-[10px] font-medium">Culture</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined" data-icon="terrain">terrain</span>
<span class="font-serif text-[10px] font-medium">Nature</span>
</div>
<div class="flex flex-col items-center justify-center text-stone-500 dark:text-stone-400 px-4 py-1">
<span class="material-symbols-outlined" data-icon="restaurant">restaurant</span>
<span class="font-serif text-[10px] font-medium">Cuisine</span>
</div>
</nav>
</body></html><!DOCTYPE html>

<html lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:wght@400;600;700&amp;family=Manrope:wght@400;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "primary-container": "#005f73",
                    "on-surface-variant": "#3f484c",
                    "on-surface": "#191c1d",
                    "on-primary-fixed": "#001f27",
                    "secondary-fixed-dim": "#ffb4ab",
                    "tertiary-container": "#7e492b",
                    "outline": "#6f797c",
                    "error": "#ba1a1a",
                    "on-error-container": "#93000a",
                    "on-secondary-container": "#fffbff",
                    "on-primary-container": "#91d7ee",
                    "primary-fixed-dim": "#8bd1e8",
                    "inverse-primary": "#8bd1e8",
                    "background": "#f8f9fa",
                    "error-container": "#ffdad6",
                    "on-primary-fixed-variant": "#004e5f",
                    "surface-container-lowest": "#ffffff",
                    "surface-container": "#edeeef",
                    "on-secondary-fixed": "#410002",
                    "on-error": "#ffffff",
                    "surface-variant": "#e1e3e4",
                    "secondary-container": "#de2e2c",
                    "on-tertiary-fixed": "#331100",
                    "outline-variant": "#bfc8cc",
                    "on-secondary-fixed-variant": "#93000d",
                    "on-secondary": "#ffffff",
                    "secondary": "#b90c17",
                    "on-background": "#191c1d",
                    "surface-tint": "#13677b",
                    "surface-container-high": "#e7e8e9",
                    "on-tertiary": "#ffffff",
                    "on-primary": "#ffffff",
                    "secondary-fixed": "#ffdad6",
                    "tertiary-fixed": "#ffdbca",
                    "surface": "#f8f9fa",
                    "on-tertiary-container": "#ffbe9c",
                    "inverse-surface": "#2e3132",
                    "primary-fixed": "#b2ebff",
                    "tertiary-fixed-dim": "#feb691",
                    "surface-bright": "#f8f9fa",
                    "tertiary": "#623317",
                    "surface-container-low": "#f3f4f5",
                    "primary": "#004655",
                    "surface-container-highest": "#e1e3e4",
                    "on-tertiary-fixed-variant": "#6b3a1d",
                    "surface-dim": "#d9dadb",
                    "inverse-on-surface": "#f0f1f2"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "full": "9999px"
            },
            "spacing": {
                    "gutter": "24px",
                    "margin-desktop": "40px",
                    "unit": "8px",
                    "margin-mobile": "16px",
                    "container-max": "1280px",
                    "section-gap": "120px"
            },
            "fontFamily": {
                    "body-md": ["Manrope"],
                    "label-sm": ["Manrope"],
                    "headline-lg": ["Noto Serif"],
                    "display-xl": ["Noto Serif"],
                    "body-lg": ["Manrope"],
                    "headline-md": ["Noto Serif"]
            },
            "fontSize": {
                    "body-md": ["16px", {"lineHeight": "1.6", "fontWeight": "400"}],
                    "label-sm": ["14px", {"lineHeight": "1.0", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "headline-lg": ["40px", {"lineHeight": "1.2", "fontWeight": "600"}],
                    "display-xl": ["64px", {"lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                    "body-lg": ["18px", {"lineHeight": "1.6", "fontWeight": "400"}],
                    "headline-md": ["28px", {"lineHeight": "1.3", "fontWeight": "600"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .oimok-pattern {
            opacity: 0.05;
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M30 0L35 25L60 30L35 35L30 60L25 35L0 30L25 25Z' fill='%23005F73'/%3E%3C/svg%3E");
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-surface text-on-surface font-body-md">
<!-- TopAppBar -->
<header class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-6 h-16 bg-[#F8F9FA] dark:bg-stone-950 shadow-[0_4px_20px_-2px_rgba(0,64,82,0.08)] border-b border-stone-200 dark:border-stone-800">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#005F73] dark:text-teal-400">menu</span>
<span class="text-2xl font-bold tracking-widest uppercase text-[#005F73] dark:text-teal-500 font-serif">Kyrgyzstan</span>
</div>
<div class="hidden md:flex items-center space-x-8">
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Главная</a>
<a class="font-serif text-[#005F73] font-bold border-b-2 border-[#D66853]" href="#">Озера</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Культура</a>
<a class="font-serif text-stone-600 dark:text-stone-400 hover:text-[#005F73] transition-all" href="#">Природа</a>
</div>
<div class="flex items-center">
<span class="material-symbols-outlined text-[#005F73] dark:text-teal-400">language</span>
</div>
</header>
<main class="pt-16">
<!-- Hero Section -->
<section class="relative h-[751px] flex items-center justify-center overflow-hidden">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover" data-alt="panoramic view of the vast turquoise issyk-kul lake surrounded by snow-capped mountains under a clear blue sky" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAF5e11l5kDShzSJUQkw9dzQzs5kd0wKhXvLttWwOP4j83oGb-Hu-eiwh1ucPk145G7NPxCPblvWNm6LDQopzpjt-5XYV8Kq9eK0dYeUEP0djEviwSHVl4U-LPLYEiZtAQuPQi443D5MDosjqkZh9kJg6tGTPhdb3HD9sZwF2MeYJ44gR7hs-FETSqyuuJp8d90rpbvmY5jn7vVssbrx4haF6YAwmFlBcsyonA_4MVI7YmeKZSepZEYmwLK2KxiLXL4dqwOuHmUTFM"/>
<div class="absolute inset-0 bg-gradient-to-b from-black/20 via-transparent to-surface/90"></div>
</div>
<div class="relative z-10 text-center px-4 max-w-4xl">
<span class="inline-block px-4 py-1 mb-6 bg-tertiary-container text-on-tertiary-container rounded-full font-label-sm uppercase tracking-widest">Жемчужина Тянь-Шаня</span>
<h1 class="font-display-xl text-white mb-6 drop-shadow-lg">Озеро Иссык-Куль</h1>
<p class="font-body-lg text-white/90 max-w-2xl mx-auto drop-shadow-md">Откройте для себя магию незамерзающего высокогорного озера, где бирюзовые волны встречаются с величественными вершинами.</p>
</div>
</section>
<!-- Cultural Divider -->
<div class="flex items-center justify-center py-section-gap px-gutter">
<div class="h-[1px] flex-grow bg-stone-200"></div>
<div class="mx-8 text-secondary">
<span class="material-symbols-outlined text-4xl" data-weight="fill">temple_buddhist</span>
</div>
<div class="h-[1px] flex-grow bg-stone-200"></div>
</div>
<!-- Beaches and Resorts (Bento-style Cards) -->
<section class="max-w-container-max mx-auto px-gutter mb-section-gap">
<div class="mb-12">
<h2 class="font-headline-lg text-primary mb-4 text-center">Пляжи и Курорты</h2>
<p class="text-on-surface-variant text-center max-w-2xl mx-auto font-body-md">От золотых песков Чолпон-Аты до уединенных диких бухт южного берега.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-12 gap-6 h-[700px]">
<div class="md:col-span-7 relative group overflow-hidden rounded-xl shadow-[0_8px_30px_rgb(0,64,82,0.12)]">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="luxurious modern resort on the shore of issyk-kul lake with outdoor pool and beach umbrellas at sunset" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB0z7C8nYf2_f64QlgQm0ChYwVK8Pb91BwCTOaUH_ShKXV_J91Jp5nqhfSimnlxDl1OoIwfvpYkuopCJVc0I7pd3cRxxE3zgt6RTne7knuM5MzkoApPLwtG4tuNiyx3v2BeI76a9Y0Nvi2KcaET-5T_ChIDPJ4mZS4LAO7A7Us53N5NvpQrN5mRpaTIMbAJrMcjzIkGWomo69Jk-qOMP9J5CfSQ-ZI0ajrZq5zSE4XxNLaiPQHtJlBfo8LjWH579hli_oU0Ewx8Vs8"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent p-8 flex flex-col justify-end">
<h3 class="font-headline-md text-white">Северный Берег</h3>
<p class="text-white/80 font-body-md">Центр развлечений, комфортабельных отелей и развитой инфраструктуры.</p>
</div>
</div>
<div class="md:col-span-5 grid grid-rows-2 gap-6">
<div class="relative group overflow-hidden rounded-xl shadow-[0_8px_30px_rgb(0,64,82,0.12)]">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="remote wild beach at issyk-kul with jagged rocks and clear turquoise water in a secluded cove" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBxRxNTE5B4SG6oXKPBlJ60yuJjEHDpmpN0tsTR08lcYZ9_sZw42PjeblSaPI5hWRjfmDkK65UjkrPrC9CSRUC6Vm2MOwTrhCSiqPYoLGLd85jSMNpM2C7J5LCClC4YfRfCaG7zes60v_Y4Q-TSXsu98qyh2i5jOOomqNNj7L2xJRMeKTpDI7nq1P382OnHFjPlmfx1G1VZZ_rx0EOZssyhFYi6KhcwLrJPTruHELupmO24VS8RVLlDwlYFynytzLR7s9mm40NiUcg"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent p-6 flex flex-col justify-end">
<h3 class="font-headline-md text-white text-xl">Южный Берег</h3>
<p class="text-white/80 text-sm">Нетронутая природа, тишина и аутентичный дух кочевников.</p>
</div>
</div>
<div class="bg-white p-8 rounded-xl flex flex-col justify-center border border-stone-100 shadow-[0_8px_30px_rgb(0,64,82,0.08)] relative overflow-hidden">
<div class="oimok-pattern absolute inset-0"></div>
<h3 class="font-headline-md text-primary mb-4 relative z-10">Золотые пески</h3>
<p class="text-on-surface-variant mb-6 relative z-10">Вода в Иссык-Куле солоноватая и никогда не замерзает, что делает его уникальным микроклиматом в сердце Центральной Азии.</p>
<button class="w-fit px-6 py-3 bg-primary text-white rounded-lg font-label-sm uppercase tracking-wider hover:translate-y-[-2px] transition-transform relative z-10">Посмотреть карту</button>
</div>
</div>
</div>
</section>
<!-- Cultural Legends (Asymmetric Layout) -->
<section class="bg-surface-container-low py-section-gap relative">
<div class="max-w-container-max mx-auto px-gutter grid grid-cols-1 md:grid-cols-2 gap-20 items-center">
<div class="order-2 md:order-1">
<div class="relative">
<img class="rounded-xl shadow-2xl z-10 relative" data-alt="mystical atmospheric photo of mist rising from a lake at dawn with a silhouette of an ancient structure" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDnEZm1AwpxsskkIc_MZGzoEeq21u7tzHpNppNnHFwr8E8cQtgFLo-eezuV6uX4JNvrRGMsd8OXZtkTJpuJ_Eq7J-0jf7MwrR1P3l6ZvZSEP997Lt_kszkk2Rlc11x-BoDrngr0Z4NAbgKQrmxy2rI2aobGp6mr90SG1U4Ws8t7SF168mxya5t-0QITXUTwKNiGRmG05skb2_nkLniZ7iBbfsDioJq7gp1zxz7zlPtvek2dhtrTGJVlz5CXPjF4rIPvGtGw9uXSK4I"/>
<div class="absolute -top-10 -left-10 w-40 h-40 bg-tertiary-fixed opacity-30 rounded-full blur-3xl -z-10"></div>
<div class="absolute -bottom-10 -right-10 w-60 h-60 bg-primary-fixed opacity-20 rounded-full blur-3xl -z-10"></div>
</div>
</div>
<div class="order-1 md:order-2">
<span class="text-secondary font-label-sm mb-4 block uppercase tracking-widest">Древнее наследие</span>
<h2 class="font-headline-lg text-primary mb-6">Легенды Священного Озера</h2>
<p class="font-body-lg text-on-surface-variant mb-8">Иссык-Куль хранит в своих глубинах тайны затонувших городов и легенды о великой любви. Самая известная из них гласит, что озеро образовалось из слез прекрасной девушки, оплакивавшей своего возлюбленного.</p>
<div class="space-y-6">
<div class="flex gap-4 items-start">
<span class="material-symbols-outlined text-tertiary text-3xl">history_edu</span>
<div>
<h4 class="font-bold text-primary">Города под водой</h4>
<p class="text-on-surface-variant">Археологи находят на дне следы древних цивилизаций, датируемых XII веком.</p>
</div>
</div>
<div class="flex gap-4 items-start">
<span class="material-symbols-outlined text-tertiary text-3xl">auto_awesome</span>
<div>
<h4 class="font-bold text-primary">Целебная сила</h4>
<p class="text-on-surface-variant">Местные жители верят, что вода озера смывает не только болезни тела, но и печаль души.</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Water Sports (Modern Glassmorphism) -->
<section class="py-section-gap">
<div class="max-w-container-max mx-auto px-gutter">
<div class="text-center mb-16">
<h2 class="font-headline-lg text-primary mb-4">Активный Отдых</h2>
<p class="text-on-surface-variant max-w-xl mx-auto">Для тех, кто ищет адреналин и энергию бирюзовых волн.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<div class="group bg-white p-2 rounded-2xl shadow-xl hover:translate-y-[-8px] transition-transform">
<div class="aspect-square rounded-xl overflow-hidden mb-6">
<img class="w-full h-full object-cover" data-alt="white sailboats on the deep blue water of issyk-kul lake with distant mountains" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCdOV_EU29vLC-Cr4S85iukHXSKgvlse4urmPGLKXi61Xd4ZSd-h-AILUmc2dkTgIt-3Fzx9w3cf2YhkqSIToWaPrGIsCl1Wyhakk7EBYm9yEQAOBSXKvp5_vt2HwK5GX4abTQ3rcvjtIoApUSA_25z8aljhPRtH3NmC243vpXSFoLfQU-ZGkwxuKoqDMF80ewGuyd71-5nXndzkr1ansp02FXUy6ovYWRCrLD5Vv1_kC6oA7HXye1QHictNQNueMp0HWYoc6Gm75k"/>
</div>
<div class="px-6 pb-6">
<h3 class="font-headline-md text-xl mb-2">Парусный спорт</h3>
<p class="text-on-surface-variant text-sm mb-4">Поймайте свежий горный ветер в паруса в бухте Каракол.</p>
<span class="material-symbols-outlined text-primary group-hover:translate-x-2 transition-transform">arrow_forward</span>
</div>
</div>
<div class="group bg-white p-2 rounded-2xl shadow-xl hover:translate-y-[-8px] transition-transform">
<div class="aspect-square rounded-xl overflow-hidden mb-6">
<img class="w-full h-full object-cover" data-alt="scuba diver underwater in clear lake water exploring rocky formations" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCzf_JaEItMbbSd6T2by49-C6nEr73AK-Gm4vbp6BCCkDr65yG_K44yUE4eX1aS-ULmTycXaMg_4koij1Vg5kI6SwXBc1RCEXRyBtSW1zef3QjpznIAgUzH06sME4N3h8UHgm7PyzG2yq7S1W1CxZ5TiBXEquWQzZNJPcisx5oA4wo6i4nJO2KkHOcNdIdoUucYQynfIuzIyGBBnhkf9SBof-RxK1Al_TFJvSe0VZghN2IGffHnmYexOEAv-hApzlnU9cJBencmS9o"/>
</div>
<div class="px-6 pb-6">
<h3 class="font-headline-md text-xl mb-2">Дайвинг</h3>
<p class="text-on-surface-variant text-sm mb-4">Исследуйте кристально чистые глубины и загадочные артефакты.</p>
<span class="material-symbols-outlined text-primary group-hover:translate-x-2 transition-transform">arrow_forward</span>
</div>
</div>
<div class="group bg-white p-2 rounded-2xl shadow-xl hover:translate-y-[-8px] transition-transform">
<div class="aspect-square rounded-xl overflow-hidden mb-6">
<img class="w-full h-full object-cover" data-alt="person riding a jet ski creating white water splashes on a sunny day at a mountain lake" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCF0wZjJsQwcOCrFWeacHMR3i7SRImzpWmY4BHyj6SX-TogR1LcUQwTFaH-P3u9RHlt3NPvkKp-LBMQrtqCJtr9VTjjIA53Qq9GiUfEyrf1y4nW_U4HUSOcROgwRaK1Lww8LhL1JV_azupjMVXf7TVW6HH68JNQ6ohyqsLqQfNMCohnpi8ZGMi_PKSI-Rae0DnAkjPz3MMjv2MxA1NORW6fs9zIw68vvdvqcT4HqBwYNXGtomsFMced3QNr5TmXlFUqtilKDu64UdM"/>
</div>
<div class="px-6 pb-6">
<h3 class="font-headline-md text-xl mb-2">Гидроциклы</h3>
<p class="text-on-surface-variant text-sm mb-4">Скорость и драйв на бескрайних водных просторах.</p>
<span class="material-symbols-outlined text-primary group-hover:translate-x-2 transition-transform">arrow_forward</span>
</div>
</div>
</div>
</div>
</section>
