# Projekts
Projekta darbs: Lietojumprogrammatūru automatizēšanas rīkos
Projekta nosaukums: Pipelife produktu/pasūtījuma lapas izveide

Šīs programmas uzdevums ir nolasīt excel lapu, kurā ir preces un to attiecīgie kodi, un izmantojot programmu ievadot attiecīgos produktu kodus un skaitu, izveidot pasūtījumu sarakstu. Šī nu gan nav ikdienas problēma ar ko saskaras ikviens, bet šo es jau labu laiku esmu vēlējies izveidot, jo esmu padzirdējis vecākus runājam par šādu programmu, kurā var viegli izveidot pasūtījumu sarakstu(Vecāki strādā Pipelife Latvia SIA, kas piedāvā plašāko plastmasas cauruļvadu sortimentu Latvijā.).

Izmantotās bibliotēkas:
    1)openpyxl - šī bibliotēka tiek izmantota, lai vieglāk strādātu ar excel failiem, šī bibliotēka strādā ar ".xlsx" failiem un izmantojot šo bibliotēku ir iespējams izveidot vienkāršu un parastiem cilvēkiem saprotamu interfeisu.
    2)csv - šī bibliotēka tiek izvēlēta tās vienkāršuma, saderības un daudzpusības dēļ CSV failu apstrādē. Tā kalpo programmas mērķim efektīvi rakstīt produktu informāciju CSV failā vienkāršā veidā.

Programma darbība - programma no sākuma nolasa excel faila pirmo kolonnu, kur ir preču kodi, un otro kolonnu, kur ir preču nosaukumi. Pēc nolasīšanas tiek prasīta lietotāja ievade, lai lietotājs ievadītu precīzu preces kodu(kas parasti atrodas šī uzņēmuma preču katalogā), un ja pēc pārbaudes būs ievadīta vēlamā prece, tad tiks prasīts ievadīt vēlamo daudzumu. Pabeidzot ievadi, preces tiek saglabātas jaunajā sarakstā, un programma jautā vai vēlaties kaut ko ievadīt. Ja vēlaties beigt programmu, tad prasot ievadiet preces kodu ievadiet 'iziet', un programma izveidos jaunu csv failu ar precēm un beigs programmas darbību.

Šo programmu var izmantot jebkurš, kurš strādā šajā uzņēmumā(vai, ja nepiciešams līdzīgās nozarēs, kas strādā ar precēm, kuru saraksts atrodas excel failā).

