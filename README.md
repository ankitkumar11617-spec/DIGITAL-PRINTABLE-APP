# Printable Notes (APK project)

App ka poora code `www/index.html` me hai. Naya feature = us ek file me change.

## APK kaise banta hai (free, cloud par)
1. github.com par account banao, New repository banao (naam: printable-notes).
2. Is folder ki saari files upload karo (Add file > Upload files). `.github` folder bhi zaroori hai.
3. Repo ke **Actions** tab me "Build APK" chalta dikhega (5-8 min).
4. Complete hone par us run par click karo, neeche **Artifacts > PrintableNotes-APK** download karo. Zip kholo, andar `app-debug.apk` hai. Phone me install karo (Unknown sources allow karna padega).

## Naya feature add karna
1. Claude se feature batao, wo updated `index.html` dega.
2. GitHub par `www/index.html` kholo, edit (pencil) ya Upload se replace karo, Commit karo.
3. Actions automatically naya APK bana dega. Wahi step 4.

## Phone me bina APK ke
`www` folder ko Netlify/GitHub Pages par host karo, Chrome me kholo, menu > Install app.
