# next-intl-bug-example-app-router

## Step

a. 在 layout 中使用getLocale 获取 locale
//const {locale} = await params;
// TODO Caused SSG build failure
const locale = await getLocale();

b. run next build -d