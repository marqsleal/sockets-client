# Simple HTTP Client

Este é um cliente HTTP simples escrito em C que se conecta a um servidor HTTP e envia uma solicitação GET para recuperar uma página web.

## Requisitos

Este projeto requer um ambiente de desenvolvimento Linux C padrão, incluindo uma Makefile utilizando CLANG e as bibliotecas de sistema padrão.

## Como Usar

1. Compile o programa a partir da Makefile utilizando o comando:
    ```
    make
    ```

2. Execute o programa, fornecendo o endereço IP ou o nome do host do servidor HTTP como argumento da linha de comando. Por exemplo (google.com):
    ```
    ./tcpc 172.217.29.206
    ```

3. O cliente enviará uma solicitação GET para o servidor e imprimirá a resposta recebida no terminal.

## Exemplo de Uso

```
$ ./tcpc 172.217.29.206
HTTP/1.1 200 OK
Date: Fri, 19 Apr 2024 00:14:54 GMT
Expires: -1
Cache-Control: private, max-age=0
Content-Type: text/html; charset=ISO-8859-1
Content-Security-Policy-Report-Only: object-src 'none';base-uri 'self';script-src 'nonce-_mGCFN7_8q9-OyJ99hskiQ' 'strict-dynamic' 'report-sample' 'unsafe-eval' 'unsafe-inline' https: http:;report-uri https://csp.withgoogle.com/csp/gws/other-hp
P3P: CP="This is not a P3P policy! See g.co/p3phelp for more info."
Server: gws
X-XSS-Protection: 0
X-Frame-Options: SAMEORIGIN
Set-Cookie: 1P_JAR=2024-04-19-00; expires=Sun, 19-May-2024 00:14:54 GMT; path=/; domain=.google.com; Secure
Set-Cookie: AEC=AQTF6Hwj8QTL_FIZswyU-sjNXockjTUGyRBBccKD4Xaf4skbcr036bMF5w; expires=Wed, 16-Oct-2024 00:14:54 GMT; path=/; domain=.google.com; Secure; HttpOnly; SameSite=lax
Set-Cookie: NID=513=c7WEx5aMpe9OzAqVSwtUylI5EEnDVNV6XYeXFlNWxC_iT1yldSSUfG0QfWjQ_z92YQytCerBx-M8dgKB0coSM-gmI2JmYtmGSvOajw2PSSPCVuqLrkfI4npFOjbcUZXZSzMegdul90t9cm1JleutvQwMH-GyXAxizJOq7mAkUvA; expires=Sat, 19-Oct-2024 00:14:54 GMT; path=/; domain=.google.com; HttpOnly
Accept-Ranges: none
Vary: Accept-Encoding
Transfer-Encoding: chunked

...
```

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar solicitações de pull (pull requests) para melhorar este projeto.

## Autor

Este projeto foi desenvolvido para fins de estudo por Gabriel F. Leal.