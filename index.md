<link href='https://cdn.fontcdn.ir/Font/Persian/Sahel/Sahel.css' rel='stylesheet' type='text/css'>

<h1>Backing Array</h1>

<div style="text-align: right;font-family: Sahel; direction: rtl; color: red">
در پشت صحنه، <code>slice</code> ها از یک <code>array</code> استفاده می کنند، که این <code>slice</code> خودش چیزی جز یک اشاره گر به یک آرایه پشتی نیست. در مثال زیر اگر به کد توجه کنید یک آرایه ساخته شده و به صورت یک <code>slice</code> درون یک آرایه ذخیره شده است، با تغییر هر عضو از این آرایه یا <code>slice</code> آن یکی هم تغییر می کند چون در نهایت این <code>slice</code> از همان آرایه به عنوان آرایه پشتی استفاده می کند.
</div>
