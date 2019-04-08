<html>
    <head>
        <title>comp3121</title>
        <script type="text/javascript">
            var queryString = window.location.search.slice(1);
            if (queryString) {
                qString = queryString.split("q=")[1].split("&")[0];
                alert(qString);
            }
            function authFunc() {
                window.location.href = "https://www.instagram.com/oauth/authorize/?client_id=6c49785b68e343b8ae060297bfa7641b&redirect_uri=https://github.com&response_type=token";
            }
        </script>
        <!-- Global site tag (gtag.js) - Google Analytics -->
        <script async src="https://www.googletagmanager.com/gtag/js?id=UA-134268415-1"></script>
        <script>
            window.dataLayer = window.dataLayer || [];
            function gtag(){dataLayer.push(arguments);}
            gtag('js', new Date());
            gtag('config', 'UA-134268415-1');
        </script>
    </head>
    <body>
        <button onClick="authFunc()"></button>        
    </body>
</html>
