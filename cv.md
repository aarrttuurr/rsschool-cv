# Artur Kandaurau

## Contact information:
- **tel:** +375 29 100-00-01
- **e-mail:** kondaurov.archi@gmail.com 
- **Discord:** aarrttuurr

## About me:
I'm 22 years old. I started my career as system administrator. But I'd like to try something completely different, gain new skills, which will allow me to prove myself better in professional life. That's why I started RS-course. 
#### My strength:
- attention to details;
- thorough approach to troubleshooting;
- teamwork skills.

## Skills
- HTML5, CSS3;
- JavaScript (fundamentals, JSON, DOM);
- Git & Github;
- SQL;
- Windows Setver & Ubuntu server.

## Education & self-education
- Belarusian State University of Iinformatics and Radioelectronics:  
    - *Information technologies and management in technical systems*;
- [learn.javascript.ru](https://learn.javascript.ru/)
- Coursera:  
    - *MIPT: HTML & CSS basics*

## Code example
Peak ***Objectify a URL Query String*** KATA from CODEWARS:

        function convertQueryToMap(query) {
          let arr = query.split('&');
          let res = arr.reduce((m, o) => {
            let vals = o.split(/[.=]/);
            vals = vals.map(item => unescape(item));
            let cur = m;
            vals.forEach((key, i) => {
              if (i < vals.length - 2) {
                cur[key] = cur[key] || {};
                cur = cur[key];
              } else if (i == vals.length - 2) {
                cur[key] = vals[vals.length - 1];
              }
            });
            return m;
          }, {})
          return res;
        }

## Languages
- **English** - A2-B1 (according to the online test at [efset](https://www.efset.org/quick-check/)) 
