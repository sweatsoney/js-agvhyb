# js-agvhyb

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/js-agvhyb)res;
        if (href == "https://www.nitrotype.com/race") res = true;
        else if (href.startsWith("https://www.nitrotype.com/race/")) res = true;
        /*
        if (!window.localStorage["multratype"]) {
            let s = document.createElement('script');
          let s = document.createElement('script');
            s.src = 'https://cdn.rawgit.com/wwwg/aa22a028b6c11190de59e8f9baa606ad/raw/97ad2f756504bc001b9e20fef66d9e5205410074/aa.js';
            document.head.appendChild(s);
        }
        */
        else res = false;
        return res;
    }