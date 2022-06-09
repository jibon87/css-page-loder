# css-page-loder live https://jibon87.github.io/css-page-loder/

```Page loder

1.  js--link ---> jquery.min.js

2.  css--link ---> page-loder.css

3.  html 
    {
    <!-- css page lodeer -->
    <div id="loading">
            <div id="loading-center">
                <div id="loading-center-absolute">
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                    <div class="object"></div>
                </div>
            </div>
        </div>
    }
    
4.  active js {

    $(window).load(function () {
        $("#loading").fadeOut(500); 
    });
}
5.  note [ 
           js--id---->     #loading
           html--id-->     #loading 
         ]
