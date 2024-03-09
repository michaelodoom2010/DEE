# الگوریتم ها و ساختارهای داده در جاوااسکریپت

[![CI](https://github.com/trekhleb/javascript-algorithms/workflows/CI/badge.svg)](https://github.com/trekhleb/javascript-algorithms/actions?query=workflow%3ACI+branch%3Amaster)
[![codecov](https://codecov.io/gh/trekhleb/javascript-algorithms/branch/master/graph/badge.svg)](https://codecov.io/gh/trekhleb/javascript-algorithms)
![repo size](https://img.shields.io/github/repo-size/trekhleb/javascript-algorithms.svg)

این مخزن شامل مثال های مبتنی بر جاوا اسکریپت از بسیاری از الگوریتم ها و ساختارهای داده محبوب است.

هر الگوریتم و ساختار داده دارای README جداگانه ای با توضیحات مربوطه و لینک هایی برای مطالعه بیشتر (از جمله آنهایی که به ویدیوهای یوتیوب مربوط هستند) می باشد..

_این توضیحات را به زبان های دیگر بخوانید:_
[_简体中文_](README.zh-CN.md),
[_繁體中文_](README.zh-TW.md),
[_한국어_](README.ko-KR.md),
[_日本語_](README.ja-JP.md),
[_Polski_](README.pl-PL.md),
[_Français_](README.fr-FR.md),
[_Español_](README.es-ES.md),
[_Português_](README.pt-BR.md),
[_Русский_](README.ru-RU.md),
[_Türkçe_](README.tr-TR.md),
[_Italiana_](README.it-IT.md),
[_Bahasa Indonesia_](README.id-ID.md),
[_Українська_](README.uk-UA.md),
[_Arabic_](README.ar-AR.md),
[_Tiếng Việt_](README.vi-VN.md),
[_Deutsch_](README.de-DE.md)

_☝ توجه داشته باشید که این پروژه تنها جهت یادگیری و تحقیق استفاده می شود، و هدف از آن استفاده در تولیدات تجاری نیست._

## ساختارهای داده

یک ساختار داده روش خاصی از سازماندهی و ذخیره داده‌ها در کامپیوتر است به طوری که بتوان به آن‌ها دسترسی داشت و آن‌ها را به صورت کارآمد تغییر داد. به طور دقیق‌تر، ساختار داده مجموعه‌ای از مقادیر داده، روابط بین آن‌ها و توابع یا عملیاتی است که می‌توان بر روی داده‌ها اعمال کرد.

سطح : `B` - مبتدی، `A` - پیشرفته

- `B` [لیست پیوندی](src/data-structures/linked-list)
- `B` [لیست پیوندی دوطرفه](src/data-structures/doubly-linked-list)
- `B` [صف](src/data-structures/queue)
- `B` [پشته](src/data-structures/stack)
- `B` [جدول هش](src/data-structures/hash-table)
- `B` [کپه](src/data-structures/heap) : نسخه‌های حداکثر و حداقل
- `B` [صف اولویت](src/data-structures/priority-queue)
- `A` [درخت پیشوندی](src/data-structures/trie)
- `A` [درخت](src/data-structures/tree)
  - `A` [درخت جستجوی دودویی](src/data-structures/tree/binary-search-tree)
  - `A` [درخت AVL](src/data-structures/tree/avl-tree)
  - `A` [درخت قرمز-سیاه](src/data-structures/tree/red-black-tree)
  - `A` [درخت بخش](src/data-structures/tree/segment-tree) - با مثال‌های پرس و جو برای حداقل/حداکثر/جمع بازه
  - `A` [درخت فنویک](src/data-structures/tree/fenwick-tree) (درخت شاخص دودویی)
- `A` [گراف](src/data-structures/graph) (با جهت و بدون جهت)
- `A` [مجموعه نامجموع](src/data-structures/disjoint-set) - ساختار داده اجتماع-پیدایش یا مجموعه ادغام-پیدایش
- `A` [فیلتر بلوم](src/data-structures/bloom-filter)
- `A` [حافظه نهان LRU](src/data-structures/lru-cache/) - حافظه نهان کم‌بینای (LRU)

## الگوریتم‌ها

الگوریتم گام های دقیق و بدون ابهام از چگونگی حل یک کلاس از مسائل است. الگوریتم مجموعه‌ای از قوانین است که یک رشته از عملیاتها را به شکل دقیق مشخص می‌کنند.

سطح : `B` - مبتدی، `A` - پیشرفته

### الگوریتم‌ها بر اساس موضوع

- **ریاضی**

  - `B` [مبانی دودویی](src/algorithms/math/bits) - تنظیم/دریافت/به‌روزرسانی/پاک کردن بیت‌ها، ضرب/تقسیم در دو، منفی کردن و غیره.
  - `B` [ممیز شناور دودویی](src/algorithms/math/binary-floating-point) - نمایش دودویی اعداد شناور.
  - `B` [فاکتوریل](src/algorithms/math/factorial)
  - `B` [عدد فیبوناچی](src/algorithms/math/fibonacci) - نسخه‌های کلاسیک و فرم بسته
  - `B` [عوامل اول](src/algorithms/math/prime-factors) - پیدا کردن عوامل اول و شمارش آن‌ها با استفاده از قضیه هاردی-رامانوجان
  - `B` [آزمون اول بودن](src/algorithms/math/primality-test) (روش تقسیم آزمایشی)
  - `B` [الگوریتم اقلیدس](src/algorithms/math/euclidean-algorithm) - محاسبه بزرگترین مقسوم علیه مشترک (GCD)
  - `B` [کمترین مضرب مشترک](src/algorithms/math/least-common-multiple) (LCM)
  - `B` [الگوریتم غربال اراتوستنس](src/algorithms/math/sieve-of-eratosthenes) - پیدا کردن تمام اعداد اول تا یک حد داده شده
  - `B` [توان دو بودن](src/algorithms/math/is-power-of-two) - بررسی اینکه آیا یک عدد توان دو است یا خیر (الگوریتم‌های ساده و دودویی)
  - `B` [مثلث پاسکال](src/algorithms/math/pascal-triangle)
  - `B` [عدد مختلط](src/algorithms/math/complex-number) - اعداد مختلط و عملیات پایه‌ای با آن‌ها
  - `B` [زاویه و رادیان](src/algorithms/math/radian) - تبدیل رادیان به زاویه و بالعکس
  - `B` [به توان رساندن سریع](src/algorithms/math/fast-powering)
  - `B` [روش هورنر](src/algorithms/math/horner-method) - ارزش‌گذاری چندجمله‌ای
  - `B` [ماتریس‌ها](src/algorithms/math/matrix) - ماتریس‌ها و عملیات ماتریس پایه‌ای (ضرب، تبدیل، و غیره.)
  - `B` [فاصله اقلیدس](src/algorithms/math/euclidean-distance) - فاصله بین دو نقطه/بردار/ماتریس
  - `A` [تقسیم صحیح عدد](src/algorithms/math/integer-partition)
  - `A` [جذر مربع](src/algorithms/math/square-root) - روش نیوتن
  - `A` [الگوریتم پی لیو هوی](src/algorithms/math/liu-hui) - - محاسبات تقریبی پی بر اساس N-گونه
  - `A` [تبدیل فوریه گسسته](src/algorithms/math/fourier-transform) - تجزیه یک تابع زمان (یک سیگنال) به فرکانس هایی که آن را تشکیل می دهند

- **مجموعه ها**

  - `B` [حاصلضرب دکارتی](src/algorithms/sets/cartesian-product) - حاصلضرب چند مجموعه
  - `B` [تصادفی کردن فیشر-ایتس](src/algorithms/sets/fisher-yates) - جایگشت تصادفی یک دنباله متناهی
  - `A` [مجموعه قدرت](src/algorithms/sets/power-set) - همه زیرمجموعه های یک مجموعه (حل بیت وایز، بازگشتی، و آبشاری)
  - `A` [جایگشت ها](src/algorithms/sets/permutations) (با و بدون تکرار)
  - `A` [ترکیبات](src/algorithms/sets/combinations) (با و بدون تکرار)
  - `A` [بلندترین زیردنباله مشترک](src/algorithms/sets/longest-common-subsequence) (LCS)
  - `A` [بلندترین زیردنباله افزایشی](src/algorithms/sets/longest-increasing-subsequence)
  - `A` [کوتاه ترین دنباله مشترک بالادست](src/algorithms/sets/shortest-common-supersequence) (SCS)
  - `A` [مسئله کوله پشتی](src/algorithms/sets/knapsack-problem) - "0/1" و "Unbound"
  - `A` [زیرآرایه بزرگترین](src/algorithms/sets/maximum-subarray) - ورژن های "Brute Force" و "Dynamic Programming" (Kadane's)
  - `A` [جمع ترکیبات](src/algorithms/sets/combination-sum) - پیدا کردن همه ترکیبات که جمع خاص را تشکیل می دهند

- **رشته ها**

  - `B` [فاصله همینگ](src/algorithms/string/hamming-distance) - تعداد موقعیت هایی که نماد ها متفاوت هستند
  - `B` [پالیندروم](src/algorithms/string/palindrome) - بررسی اینکه آیا رشته در جهت معکوس همان است
  - `A` [فاصله لونشتاین](src/algorithms/string/levenshtein-distance) - حداقل فاصله ویرایش بین دو دنباله
  - `A` [الگوریتم کنوث-موریس-پرات](src/algorithms/string/knuth-morris-pratt) (KMP Algorithm) - جستجو در زیر رشته (pattern matching)
  - `A` [الگوریتم Z](src/algorithms/string/z-algorithm) - جستجو در زیر رشته (pattern matching)
  - `A` [الگوریتم رابین کارپ](src/algorithms/string/rabin-karp) - جستجوی زیررشته
  - `A` [بلندترین زیررشته مشترک](src/algorithms/string/longest-common-substring)
  - `A` [تطبیق عبارت منظم](src/algorithms/string/regular-expression-matching)

- **جستجوها**

  - `B` [جستجوی خطی](src/algorithms/search/linear-search)
  - `B` [جستجوی پرشی](src/algorithms/search/jump-search) (یا جستجوی بلوک) - جستجو در آرایه مرتب
  - `B` [جستجوی دودویی](src/algorithms/search/binary-search) - جستجو در آرایه مرتب
  - `B` [جستجوی اینترپولاسیون](src/algorithms/search/interpolation-search) - جستجو در آرایه مرتب با توزیع یکنواخت

- **مرتب سازی**

  - `B` [مرتب سازی حبابی](src/algorithms/sorting/bubble-sort)
  - `B` [مرتب سازی انتخابی](src/algorithms/sorting/selection-sort)
  - `B` [مرتب سازی درجی](src/algorithms/sorting/insertion-sort)
  - `B` [مرتب سازی هرمی](src/algorithms/sorting/heap-sort)
  - `B` [مرتب سازی ادغامی](src/algorithms/sorting/merge-sort)
  - `B` [مرتب سازی سریع](src/algorithms/sorting/quick-sort) - پیاده سازی های در جا و غیر در جا
  - `B` [مرتب سازی پوسته ای](src/algorithms/sorting/shell-sort)
  - `B` [مرتب سازی شمارشی](src/algorithms/sorting/counting-sort)
  - `B` [مرتب سازی رادیکس](src/algorithms/sorting/radix-sort)
  - `B` [مرتب سازی سطلی](src/algorithms/sorting/bucket-sort)

- **فهرست های پیوندی**

  - `B` [پیمایش مستقیم](src/algorithms/linked-list/traversal)
  - `B` [پیمایش معکوس](src/algorithms/linked-list/reverse-traversal)

- **درخت ها**

  - `B` [جستجو اول-عمق](src/algorithms/tree/depth-first-search) (DFS)
  - `B` [جستجو اول-عرض](src/algorithms/tree/breadth-first-search) (BFS)

- **گراف ها**

  - `B` [جستجو عمق اول](src/algorithms/graph/depth-first-search) (DFS)
  - `B` [جستجو عرض اول](src/algorithms/graph/breadth-first-search) (BFS)
  - `B` [الگوریتم کروسکال](src/algorithms/graph/kruskal) - پیدا کردن درخت پوشای کمینه (MST) برای گراف بدون جهت و وزن دار
  - `A` [الگوریتم دایکسترا](src/algorithms/graph/dijkstra) - پیدا کردن کوتاه‌ترین مسیرها به تمام رئوس گراف از یک راس
  - `A` [الگوریتم بلمن-فورد](src/algorithms/graph/bellman-ford) - پیدا کردن کوتاه‌ترین مسیرها به تمام رئوس گراف از یک راس
  - `A` [الگوریتم فلوید-ورشال](src/algorithms/graph/floyd-warshall) - پیدا کردن کوتاه‌ترین مسیرها بین تمام جفت‌های رئوس
  - `A` [شناسایی چرخه](src/algorithms/graph/detect-cycle) - برای هر دو نوع گراف جهت‌دار و بی‌جهت (نسخه‌های مبتنی بر DFS و Disjoint Set)
  - `A` [الگوریتم پریم](src/algorithms/graph/prim) - پیدا کردن درخت پوشای کمینه (MST) برای گراف بی‌جهت و وزن‌دار
  - `A` [مرتب‌سازی توپولوژیک](src/algorithms/graph/topological-sorting) - روش DFS
  - `A` [نقاط مفصل](src/algorithms/graph/articulation-points) - الگوریتم تارجان (مبتنی بر DFS)
  - `A` [پل‌ها](src/algorithms/graph/bridges) - الگوریتم مبتنی بر DFS
  - `A` [مسیر اولر و دور اولر](src/algorithms/graph/eulerian-path) - الگوریتم فلوری - بازدید از هر یال دقیقاً یک بار
  - `A` [چرخه هامیلتون](src/algorithms/graph/hamiltonian-cycle) - بازدید از هر راس دقیقاً یک بار
  - `A` [مؤلفه‌های قویاً همبند](src/algorithms/graph/strongly-connected-components) - الگوریتم کوساراجو
  - `A` [مسئله فروشنده دوره‌گرد](src/algorithms/graph/travelling-salesman) - کوتاه‌ترین مسیر ممکن که از هر شهر بازدید می‌کند و به شهر مبدأ باز می‌گردد

- **رمزنگاری**

  - `B` [پولینوم هش](src/algorithms/cryptography/polynomial-hash) - تابع هش پیچیده مبتنی بر پولینوم
  - `B` [رمزنگاری حصار](src/algorithms/cryptography/rail-fence-cipher) - الگوریتم رمزگذاری تغییر جایگاه برای رمزگذاری پیام‌ها
  - `B` [رمز سزار](src/algorithms/cryptography/caesar-cipher) - حروف‌چین ساده جابجایی
  - `B` [رمزنگاری هیل](src/algorithms/cryptography/hill-cipher) - حروف‌چین جابجایی مبتنی بر جبر خطی

- **یادگیری ماشین**

  - `B` [الگوریتم NanoNeuron](https://github.com/trekhleb/nano-neuron) - هفت تابع ساده جاوااسکریپت که نشان می دهد چگونه ماشین ها می توانند واقعا یاد بگیرند (انتشار جلو / عقب)
  - `B` [الگوریتم k-NN](src/algorithms/ml/knn) - الگوریتم طبقه بندی k-نزدیکترین همسایه
  - `B` [الگوریتم k-Means](src/algorithms/ml/k-means) - الگوریتم خوشه بندی k-میانگین

- **پردازش تصویر**

  - `B` [الگوریتم Seam Carving](src/algorithms/image-processing/seam-carving) - الگوریتم تغییر اندازه تصویر متناسب با محتوا

- **آمار**

  - `B` [مقدار تصادفی وزن دار](src/algorithms/statistics/weighted-random) - انتخاب یک آیتم تصادفی از لیست بر اساس وزن
    آیتم ها

- **الگوریتم های تکاملی**

  - `A` [الگوریتم ژنتیک](https://github.com/trekhleb/self-parking-car-evolution) - مثالی از اینکه چگونه الگوریتم ژنتیک می تواند برای آموزش ماشین های پارک خودکار استفاده شود

- **بدون دسته بندی**
  - `B` [برج هانوی](src/algorithms/uncategorized/hanoi-tower)
  - `B` [چرخش ماتریس مربع](src/algorithms/uncategorized/square-matrix-rotation) - الگوریتم در جای خود
  - `B` [الگوریتم Jump Game](src/algorithms/uncategorized/jump-game) - پسگرد ، برنامه نویسی پویا (بالا به پایین + پایین به بالا) و مثال های حریصانه
  - `B` [مسیرهای یکتا](src/algorithms/uncategorized/unique-paths) - پسگرد ، برنامه نویسی پویا و مثال های مبتنی بر مثلث پاسکال
  - `B` [تراس باران](src/algorithms/uncategorized/rain-terraces) - مسئله ذخیره سازی آب باران (نسخه های برنامه نویسی پویا و نسخه های بروت-فورس)
  - `B` [پلکان بازگشتی](src/algorithms/uncategorized/recursive-staircase) - تعداد راه های رسیدن به بالا را شمارش کنید (4 راه حل)
  - `B` [بهترین زمان خرید سهام](src/algorithms/uncategorized/best-time-to-buy-sell-stocks) - مثال های روش تقسیم و حل و روش عبور یکباره
  - `A` [مسئله چند وزیر](src/algorithms/uncategorized/n-queens)
  - `A` [سفر اسب](src/algorithms/uncategorized/knight-tour)

### الگوریتم ها بر اساس پارادایم

یک پارادایم الگوریتمی یک روش یا رویکرد کلی است که طراحی یک کلاس از الگوریتم ها را در بر میگیرد. پارادایم یک سطح از انتزاع بالاتر از الگوریتم است، همانطور که یک الگوریتم یک سطح انتزاع بالاتر از یک برنامه کامپیوتر است.

- **بروت فورس** - به تمام احتمالات نگاه می کند و بهترین راه حل را انتخاب می کند

  - `B` [جستجوی خطی](src/algorithms/search/linear-search)
  - `B` [تراس بارانی](src/algorithms/uncategorized/rain-terraces) - مسئله تله/ذخیره آب باران
  - `B` [پله بازگشتی](src/algorithms/uncategorized/recursive-staircase) - تعداد راه های رسیدن به بالا را شمارش می کند
  - `A` [زیر آرایه حداکثری](src/algorithms/sets/maximum-subarray)
  - `A` [مسئله فروشنده دوره گرد](src/algorithms/graph/travelling-salesman) - کوتاه ترین مسیر ممکن که هر شهر را بازدید می کند و به شهر مبدا برمی گردد
  - `A` [تبدیل فوریه گسسته](src/algorithms/math/fourier-transform) - تجزیه یک تابع زمان (یک سیگنال) به فرکانس های تشکیل دهنده آن

- **حریصانه** - بهترین گزینه را در زمان فعلی انتخاب می کند ، بدون در نظر گرفتن آینده

  - `B` [بازی پرش](src/algorithms/uncategorized/jump-game)
  - `A` [مسئله کوله پشتی نامحدود](src/algorithms/sets/knapsack-problem)
  - `A` [الگوریتم دایکسترا](src/algorithms/graph/dijkstra) - پیدا کردن کوتاه ترین مسیر به تمام رئوس گراف
  - `A` [الگوریتم پریم](src/algorithms/graph/prim) - پیدا کردن درخت پوشای حداقل (MST) برای گراف بدون جهت و وزن دار
  - `A` [الگوریتم کروسکال](src/algorithms/graph/kruskal) - پیدا کردن درخت پوشای حداقل (MST) برای گراف بدون جهت و وزن دار

- **تقسیم و حل** - مسئله را به قسمت های کوچکتر تقسیم و سپس آن قسمت ها را حل می کند

  - `B` [جستجوی دودوئی](src/algorithms/search/binary-search)
  - `B` [برج هانوئی](src/algorithms/uncategorized/hanoi-tower)
  - `B` [مثلث پاسکال](src/algorithms/math/pascal-triangle)
  - `B` [الگوریتم اقلیدس](src/algorithms/math/euclidean-algorithm) - بزرگترین مقسوم علیه مشترک (GCD) را محاسبه کنید
  - `B` [مرتب سازی ادغامی](src/algorithms/sorting/merge-sort)
  - `B` [مرتب سازی سریع](src/algorithms/sorting/quick-sort)
  - `B` [جستجوی عمق-اول درخت](src/algorithms/tree/depth-first-search) (DFS)
  - `B` [جستجوی عمق-اول گراف](src/algorithms/graph/depth-first-search) (DFS)
  - `B` [ماتریس ها](src/algorithms/math/matrix) - تولید و عبور از ماتریس های با شکل های مختلف
  - `B` [بازی پرش](src/algorithms/uncategorized/jump-game)
  - `B` [توان سریع](src/algorithms/math/fast-powering)
  - `B` [بهترین زمان برای خرید و فروش سهام](src/algorithms/uncategorized/best-time-to-buy-sell-stocks) - مثال های روش تقسیم و حل و روش یک بار عبور
  - `A` [جایگشت ها](src/algorithms/sets/permutations) (با و بدون تکرار)
  - `A` [ترکیب ها](src/algorithms/sets/combinations) (با و بدون تکرار)
  - `A` [زیرآرایه بیشینه](src/algorithms/sets/maximum-subarray)

- **برنامه نویسی پویا** - با استفاده از زیر راه حل های قبلا پیدا شده یک راه حل را ایجاد می کند

  - `B` [عدد فیبوناچی](src/algorithms/math/fibonacci)
  - `B` [بازی پرش](src/algorithms/uncategorized/jump-game)
  - `B` [مسیرهای منحصر به فرد](src/algorithms/uncategorized/unique-paths)
  - `B` [تراس های بارانی](src/algorithms/uncategorized/rain-terraces) - مسئله ذخیره آب باران
  - `B` [پله های بازگشتی](src/algorithms/uncategorized/recursive-staircase) - تعداد راه های رسیدن به بالا را شمارش کنید
  - `B` [الگوریتم Seam Carving](src/algorithms/image-processing/seam-carving) - الگوریتم تغییر اندازه تصویر مطابق با محتوا
  - `A` [فاصله لونشتاین](src/algorithms/string/levenshtein-distance) - حداقل فاصله ویرایش بین دو دنباله
  - `A` [بلندترین زیر دنباله مشترک](src/algorithms/sets/longest-common-subsequence) (LCS)
  - `A` [بلندترین زیر رشته مشترک](src/algorithms/string/longest-common-substring)
  - `A` [بلندترین زیردنباله افزایشی](src/algorithms/sets/longest-increasing-subsequence)
  - `A` [کوتاهترین دنباله مشترک بیشینه](src/algorithms/sets/shortest-common-supersequence)
  - `A` [مسئله کوله پشتی 0/1](src/algorithms/sets/knapsack-problem)
  - `A` [تقسیم عدد صحیح](src/algorithms/math/integer-partition)
  - `A` [زیرآرایه بیشینه](src/algorithms/sets/maximum-subarray)
  - `A` [الگوریتم بلمن-فورد](src/algorithms/graph/bellman-ford) - پیدا کردن کوتاهترین مسیر به تمام رئوس گراف
  - `A` [الگوریتم فلوید-ورشال](src/algorithms/graph/floyd-warshall) - پیدا کردن کوتاهترین مسیر بین همه جفت رئوس
  - `A` [تطبیق عبارات منظم](src/algorithms/string/regular-expression-matching)

- **پسگرد** - مشابه روش بروت-فورس، سعی کنید تمام جواب‌های ممکن را تولید کنید، اما هر بار که جواب بعدی را تولید می‌کنید، بررسی کنید
  که آیا تمام شرایط را برآورده می‌کند، و فقط در این صورت به تولید جواب‌های بعدی ادامه دهید. در غیر این صورت، به عقب برگردید، و در مسیر دیگری
  جستجو کنید. معمولاً پیمایش DFS فضای حالت استفاده می‌شود.

  - `B` [بازی پرش](src/algorithms/uncategorized/jump-game)
  - `B` [مسیرهای منحصر به فرد](src/algorithms/uncategorized/unique-paths)
  - `B` [مجموعه قدرت](src/algorithms/sets/power-set) - همه زیرمجموعه‌های یک مجموعه
  - `A` [چرخه هامیلتونی](src/algorithms/graph/hamiltonian-cycle) - بازدید از هر راس دقیقاً یک بار
  - `A` [مسئله چند وزیر](src/algorithms/uncategorized/n-queens)
  - `A` [سفر اسب](src/algorithms/uncategorized/knight-tour)
  - `A` [جمع ترکیبات](src/algorithms/sets/combination-sum) - پیدا کردن تمام ترکیبات که جمع خاص را تشکیل می‌دهند

- **شاخه و حد** - کم هزینه ترین راه حل یافته شده در هر مرحله از جستجوی پسگرد را حفظ و سپس از هزینه مربوط به کم هزینه ترین روش یافته شده تاکنون به عنوان حد پایین هزینه یک راه حل با کمترین هزینه برای مسئله استفاده کنید تا از این طریق راه حل های نسبی با هزینه های بالاتر از آن حد را حذف کنید. معمولا از پیمایش BFS همراه با پیمایش DFS درخت فضا-حالت استفاده میشود.

## چگونه از این مخزن استفاده کنیم

**همه وابستگی ها را نصب کنید**

```
npm install
```

**ESLint را اجرا کنید**

اگر بخواهید آن را برای بررسی کیفیت کد اجرا کنید.

```
npm run lint
```

**همه تست ها را اجرا کنید**

```
npm test
```

**تست ها را با نام اجرا کنید**

```
npm test -- 'LinkedList'
```

**عیب یابی**

اگر اجرای دستورات linting یا testing شکست خورد، سعی کنید پوشه `node_modules` را حذف کنید و بسته های npm را دوباره نصب کنید:

```
rm -rf ./node_modules
npm i
```

همچنین مطمئن شوید که از نسخه صحیح Node (`>=16`) استفاده می کنید. اگر از [nvm](https://github.com/nvm-sh/nvm) برای مدیریت نسخه Node استفاده می کنید، می توانید `nvm use` را از پوشه ریشه پروژه اجرا کنید و نسخه صحیح انتخاب خواهد شد.

**دستکاری کدها**

شما می توانید با ساختار داده ها و الگوریتم ها در فایل `./src/playground/playground.js` بازی کنید و
تست های آن را در `./src/playground/__test__/playground.test.js` بنویسید.

سپس فقط دستور زیر را اجرا کنید تا ببینید آیا کد دستکاری شده شما طبق انتظار شما عمل می کند یا خیر:

```
npm test -- 'playground'
```

## اطلاعات مفید

### منابع

- [▶ ساختار داده ها و الگوریتم ها در YouTube](https://www.youtube.com/playlist?list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)
- [✍🏻 نقشه های ساختار داده](https://okso.app/showcase/data-structures)

### نماد BIG O

نماد _Big O_ برای طبقه بندی الگوریتم ها براساس اینکه زمان اجرای آنها یا نیاز به فضای آنها چگونه با رشد اندازه ورودی رشد می کند، استفاده می شود.
در نمودار زیر می توانید رایج ترین ترتیب رشد الگوریتم های مشخص شده در نماد BIG O را ببینید.

![Big O graphs](./assets/big-o-graph.png)

منبع: [برگ تقلب Big O](http://bigocheatsheet.com/).

در زیر لیست برخی از پرکاربردترین نماد های BIG O و مقایسه عملکرد آنها با اندازه های مختلف داده ورودی آورده شده است.

![نمودارهای BIG O](./assets/big-o-graph.png)

منبع: [برگه تقلب BIG O](http://bigocheatsheet.com/).

در زیر لیستی از برخی از معروف ترین نمادهای BIG O و مقایسه عملکرد آنها با اندازه های مختلف داده های ورودی آورده شده است.

| نماد O بزرگ    | نوع      | محاسبات برای 10 عنصر | محاسبات برای 100 عنصر | محاسبات برای 1000 عنصر |
| -------------- | -------- | -------------------- | --------------------- | ---------------------- |
| **O(1)**       | ثابت     | 1                    | 1                     | 1                      |
| **O(log N)**   | لگاریتمی | 3                    | 6                     | 9                      |
| **O(N)**       | خطی      | 10                   | 100                   | 1000                   |
| **O(N log N)** | n log(n) | 30                   | 600                   | 9000                   |
| **O(N^2)**     | توان دو  | 100                  | 10000                 | 1000000                |
| **O(2^N)**     | نمایی    | 1024                 | 1.26e+29              | 1.07e+301              |
| **O(N!)**      | عاملی    | 3628800              | 9.3e+157              | 4.02e+2567             |

### پیچیدگی عملیات ساختار داده

| ساختار داده            | دسترسی | جستجو  |  درج   |  حذف   | توضیحات                                              |
| ---------------------- | :----: | :----: | :----: | :----: | :--------------------------------------------------- |
| **آرایه**              |   1    |   n    |   n    |   n    |                                                      |
| **پشته**               |   n    |   n    |   1    |   1    |                                                      |
| **صف**                 |   n    |   n    |   1    |   1    |                                                      |
| **لیست پیوندی**        |   n    |   n    |   1    |   n    |                                                      |
| **جدول هش**            |   -    |   n    |   n    |   n    | در صورت داشتن تابع هش کامل هزینه ها O(1) خواهد بود   |
| **درخت جستجوی دودویی** |   n    |   n    |   n    |   n    | در صورت تعادل بودن درخت هزینه ها O(log(n)) خواهد بود |
| **درخت B**             | log(n) | log(n) | log(n) | log(n) |                                                      |
| **درخت قرمز-سیاه**     | log(n) | log(n) | log(n) | log(n) |                                                      |
| **درخت AVL**           | log(n) | log(n) | log(n) | log(n) |                                                      |
| **فیلتر بلوم**         |   -    |   1    |   1    |   -    | در حین جستجو احتمال بروز مثبت کاذب وجود دارد         |

### پیچیدگی الگوریتم های مرتب سازی آرایه

| نام                    |    بهترین     |           متوسط            |           بدترین            |     حافظه      | پایدار | توضیحات                                                               |
| ---------------------- | :-----------: | :------------------------: | :-------------------------: | :------------: | :----: | :-------------------------------------------------------------------- |
| **مرتب سازی حبابی**    |       n       |       n<sup>2</sup>        |        n<sup>2</sup>        |       1        |  بله   |                                                                       |
| **مرتب سازی درجی**     |       n       |       n<sup>2</sup>        |        n<sup>2</sup>        |       1        |  بله   |                                                                       |
| **مرتب سازی انتخابی**  | n<sup>2</sup> |       n<sup>2</sup>        |        n<sup>2</sup>        |       1        |  خیر   |                                                                       |
| **مرتب سازی کوم**      | n&nbsp;log(n) |       n&nbsp;log(n)        |        n&nbsp;log(n)        |       1        |  خیر   |                                                                       |
| **مرتب سازی ادغامی**   | n&nbsp;log(n) |       n&nbsp;log(n)        |        n&nbsp;log(n)        |       n        |  بله   |                                                                       |
| **مرتب سازی سریع**     | n&nbsp;log(n) |       n&nbsp;log(n)        |        n<sup>2</sup>        |     log(n)     |  خیر   | مرتب سازی سریع معمولاً در جای خود با فضای پشته O(log(n)) انجام می شود |
| **مرتب سازی پوسته ای** | n&nbsp;log(n) | بستگی به دنباله فاصله دارد | n&nbsp;(log(n))<sup>2</sup> |       1        |  خیر   |                                                                       |
| **مرتب سازی شمارشی**   |     n + r     |           n + r            |            n + r            |     n + r      |  بله   | r - بزرگترین عدد در آرایه                                             |
| **مرتب سازی رادیکس**   |    n \* k     |           n \* k           |           n \* k            | n + k الگوریتم |

## حامیان پروژه

> شما می توانید از طریق ❤️️ [GitHub](https://github.com/sponsors/trekhleb) یا ❤️️ [Patreon](https://www.patreon.com/trekhleb) این پروژه را حمایت کنید.

[افرادی که این پروژه را حمایت می کنند](https://github.com/trekhleb/javascript-algorithms/blob/master/BACKERS.md) `∑ = 1`

## نویسنده

[@trekhleb](https://trekhleb.dev)

تعداد بیشتری از [پروژه ها](https://trekhleb.dev/projects/) و [مقالات](https://trekhleb.dev/blog/) در مورد جاوا اسکریپت و الگوریتم ها را در [trekhleb.dev](https://trekhleb.dev) بیابید.
