## instagram.com

* 🎉 One of the first webpack users
* ⌛️ **Long Term Caching** with chunkhash
* 📦 1 vender chunk
* 📦 page app chunks (**Page Shell**)
* 📡📦 36 on demand page chunks

---

---

## airbnb.com

* ⌛️ **Long Term Caching** with chunkhash
* 📡📦 **&gt; 400 chunks**
* 📦 header and footer chunks
* 📦 app chunk
* 📦 page chunks
* 📡📦 on demand chunks
* 🔋 Service Worker (cache: **search only**)

---

---

## trivago.de

* 📌 **targeted build** (many combinations)
* 🏰 **SSR**
* ⌛️ **Long Term Caching** with chunkhash
* 📦 **DLL** bundled vendors (use by both bundles)
* 📦 **separate** bundle for **important features**
* 📡📦 48 **on demand** chunks (progressive enhanced)
  * very tiny (some could be merged => `MinChunkSizePlugin`)

---

---

## housing.com (mobile)

* ⌛️ **Long Term Caching** with chunkhash
* 📦 1 vender chunk
* 📦 1 app chunk (App Shell)
* 📦 35 page chunks
* 🔋 **Service Worker** (App and Content)
  * Content on "shortlist" is offline available
  * Great UX for visualizing offline content

---

---

## twitter.com

* 📌 **targeted build** (per language)
* 🏰 **SSR**
* ⌛️ **Long Term Caching** with chunkhash
* 📦 1 init chunk (**App Shell**)
* 📦 1 common chunk
* 📦 12 page chunks
* 📡📦 3 on demand chunks
* Service Worker (only for Push Notification 🤔)

---

---

## mobile.twitter.com

* **targeted build** (`ltr`, `rtl`)
* **Long Term Caching** with chunkhash
* 1 manifest chunk (but not inlined 🤔)
* 📦 1 vendor chunk
* 📦 1 app chunk (**App Shell**)
* 📦 44 **language chunks** (globalize-webpack-plugin)
* 📦 37 page chunks
* 📡📦 4 on demand chunks
* 🔋 **Service Worker** (serving App and Content)
* https://blog.twitter.com/2017/how-we-built-twitter-lite
