# Extra

## **Web Hosting** {#web-hosting}

Once you have finished all customization, The next step is to upload your event website to a Live Hosting Server. For that you will need to buy a Hosting Plan and a Domain name from a Service Provider. If you already have a domain and space, you can skip this. Else read on.

### **Affordable Hosting & Domain** {#affordable-hosting-and-domain}

As an Author, I can provide you cheap and affordable Shared Hosting Plan \(Linux with PHP\) with a Domain name. If you purchased Hosting from me, I can also help you to Upload the files correctly to the server for you. Please note that this is a Shared Hosting Plan, and if you want to host a big traffic website, Try buying VPS or Dedicated Server from other providers. Please note that the complete event website will be less than 20 MB.

### Hosting Plans {#hosting-plans}

| **Plan** | **Space** | **Bandwidth \(MB\)** | **Price \(USD\)** |
| --- | --- | --- | --- | --- | --- | --- |
| Basic | 50 MB | 1000 | $20 / year |
| LITE | 100 MB | 2000 | $30 / year |
| SILVER | 250 MB | 2500 | $40 / year |
| GOLD | 500 MB | 5000 | $50 / year |
| PLATINUM | 1 GB | 10,000 | $80 / year |
| CUSTOM | \(your choice\) | \(your choice\) | \(contact us\) |

Domain prices starts from **USD 15.00** per year \(.com, .net, .in, .org, .co.in etc..\)

## **Uploading to Server** {#uploading-to-server}

 Once you have registered a domain name and Hosting, You will get FTP details from your hosting provider. Use that login details to connect with your server. You will need an FTP Software for this such as [FileZilla](https://filezilla-project.org/download.php?type=client). Connect with your server and open `/public_html` folder in your server. Then copy all HTML, CSS and JS files from your local machine to your root `/public_html` folder in your server. Please note the HTML files should be in the Server's root folder. If your local project is in `/your-folder/` Do not upload the folder directly. Instead open the folder and select all HTML files and CSS, JS folders and upload.

## **Website Optimization Tips** {#website-optimization-tips}

A Fast & Optimized Website has several factors which needs to be implemented in order to achieve the desired results. There are several Optimization Techniques available which will definitely affect your Website's Performance in a Positive Way & we want to share a few of them with you:

### **GZip Compression & Browser Caching** {#gzip-compression-and-browser-caching}

This is probably one of the Most Important Techniques you should definitely implement in order to bump up your Website's Loading Speed. **GZip Compression** is used to compress the Files that are delivered when loading a Website. It covers HTML, CSS, JavaScript & Font Files along with other miscellaneous text files. Where as **Browser Caching** also covers Images & Videos apart from including the above files. This is used to saves the Static Data in your Browser itself so that when you open the Next Pages on the Same Website, the content does not gets Downloaded again, loading the Website fast.

**GZip Compression** & **Browser Caching** can be enabled using the `.htaccess` File on an Apache Web Server. You can use the Codes from here: [https://github.com/h5bp/html5-boilerplate/blob/master/dist/.htaccess](https://github.com/h5bp/html5-boilerplate/blob/master/dist/.htaccess) to enable these modules on your server.

### **Image Compression & Optimization** {#image-compression-and-optimization}

We tend to use Lots of Images on our Websites but we often do not make efforts to Compress & Optimize them. Remember, the Larger the Image, the more time it takes to download and therefore this slows your website loading times affecting User Experience. Your customer will leave your website if it does not load within 3-5 Seconds which adversely affects your Sales. Therefore, it is important to Resize, Optimize & Compress your Images before using it on your Website. Here are some Tips which might come handy in optimizing images:

1. **Resize your Images:** Resize your Images before using it on your Website. Do not just Download an Image & place it as it is in your Website's `<img>` Tag without resizing it. The size/resolution of the Image matters since it is not recommended to use an Image size of `1200px` x `800px` in a Content Size of `300px` x `200px` as this is unnecessary. Resize it to `300px` x `200px`
2. **Image Formats:** There are three common file types that are used for web images which are JPEG, GIF, & PNG. For images with a Flat Background use **JPEG** images, for images with a Transparent background use **PNG** images and for images with Animations use **GIF** images.
3. **Compressing Images:** Images Compression is important as it considerably reduces the size without losing the quality. There are several FREE Image Optimization Tools available to Download. **For MAC** use [ImageOptim](https://imageoptim.com/) \| **For Windows** use [Riot](http://luci.criosweb.ro/riot/) for compressing JPEG Images & [PNG Gauntlet](http://pnggauntlet.com/) for PNG Images.

### **CSS & jQuery Minification**  {#css-and-jquery-minification}

It is also recommended that you **Combine & Minify** all your CSS Files to a single CSS File & all Javascript Files to a single JS File since **Minification** reduces the size of the File and **Combining** the files helps in reducing the number of HTTP requests made to the server. This is also an Important Factor in increasing the speed of your website. There are several tools available online to Minify your CSS & JS Files. Our recommendations are: **For CSS** use [CSS Minifier](http://cssminifier.com/) and **For Javascript** use [Javascript Minifier](http://javascript-minifier.com/).

### **Content Delivery Network** {#content-delivery-network}

You can use a **CDN** to further speed up your website. You can use the CDN to deliver static files of your website like CSS, JS, Images & Font Files. There are several CDN Hosting Providers available on the Internet but we would recommend [MaxCDN](https://www.maxcdn.com/) or [CloudFlare](http://www.cloudflare.com/). Note: CDN setup requires Extra monthly Fees to setup, so it is completely optional & according to your needs. Cloudflare also has a Free plan, you can try that for free.

### **Fast Web Hosting Servers** {#fast-web-hosting-servers}

A lot depends on your Web Hosting Servers, so it is recommended that you choose a Hosting Company/Server that provides a Reliable & a Fast Hosting Service. You can also choose our shared hosting plans. See above.

