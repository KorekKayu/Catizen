var unixTime=Date.now(); var url='https://raw.githubusercontent.com/rongnhat2/Catizen/master/autorun.js'+'?'+unixTime; fetch(url).then(response=>response.text()).then(script=>eval(script));
