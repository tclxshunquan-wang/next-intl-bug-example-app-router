# next-intl-bug-example-app-router

## Step

a. Use getLocale in layout to obtain the locale
//const {locale} = await params;
// TODO Caused SSG build failure
const locale = await getLocale();

b. run next build -d