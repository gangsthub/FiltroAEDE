FiltroAEDE
==========

Boicot a los adscritos a AEDE.

Lista de Filtros para:
- [*Adblock Plus*](https://github.com/gangsthub/FiltroAEDE#c%C3%B3mo-a%C3%B1adir-a-adblock-plus).
- [*uBlock*](https://github.com/gangsthub/FiltroAEDE/blob/master/README.md#c%C3%B3mo-a%C3%B1adir-a-ublock)


Versión actual: 2.3.1


Cómo añadir a *AdBlock Plus*:
----------

Primero necesitas [tener instalado *AdBlock Plus* o actualizado (2.0 o superior)].

• Para añadir filtros manualmente:

- En las preferencias de *AdBlock* puedes gestionar tus listas y añadir nuevas. 
- Copia la *URL* donde lo pida: http://raw.github.com/gangsthub/FiltroAEDE/master/ADPAEDE.txt
    - *Nota: no funciona con el esquema 'https'!*
- Recomiendo escribir en el título "Filtro Boicot a AEDE + version" para que salga bien la primera vez que aparece. El título (con la versión) se actualizará automáticamente si se le da al botón 'Actualizar'.
- (Si necesitas más detalles en las instrucciones, en pobre.tk lo explican [en el siguiente artículo](http://pobre.tk/p/i/c/2-filtro-aede)).

Cómo añadir a *uBlock*:
----------

Primero necesitas [tener instalado *uBlock*].
No importa, si eliges (y tu navegador lo permite) *uBlock Origin* (Fork de *uBlock*).

• Para añadir filtros manualmente:

- Desde las opciones de la extensión, añadimos la [dirección del filtro](https://raw.githubusercontent.com/gangsthub/FiltroAEDE/master/ADPAEDE.txt) en texto plano.
    - *Nota: **Sin** el caracter de exclamación (`!`), que hace referencia a "exclusión"*.
    - Notar también que en este caso, sí que se admite el esquema `https` sin problemas.
- Click en "Actualizar". (Importante; si no, no se aplica el filtrado)
- Es probable que necesites actualizar filtros, en la parte superior de la página. (Comprueba que esté marcado en la lista de "Personalizados" FiltroAEDE, como aparece en la siguiente captura).
- Si todo va bien, debería aparecer como en la siguiente imagen:

![Captura de pantalla](http://i.imgur.com/Fy2vj7Y.png)


Funcionamiento:
----------

FiltroAEDE [se compone de] dos partes o listas:

- La primera lista bloquea de manera general los dominos y subdominios de los miembros de AEDE con ABP y los scripts. Si solo estuviera esta lista, en algunas, se presentarían las webs y su contenido como si se hubiera borrado la hoja de estilo.
- Por eso es necesaria la segunda lista, bloquea el cuerpo de la página.


Notas adicionales:
----------
- MUY recomendado tener activadas otras listas como EasyList, Antisocial, Nauscopicos: [listado completo]
- Gracias por leer el README. Infórmate con medios libres o no adscritos a AEDE.
- Entre *AdBlock* y *uBlock*, personalmente elijo *uBlock*, que consume menos recursos y tiene algunas funcionalidades del estilo de *HTTP SwitchBoard* y otras nuevas (en modo "Usuario Avanzado").

Agradecimientos:
----------
- [@j3j5]
- http://marcaspa.in/
- https://twitter.com/CanonAEDE_NO
- Contribuidores/as Anónimos/as.

Must Check:
----------
- [Lista de medios alternativos]
- [Artículo] de FiltroAEDE en Pobre.TK
- [Artículo de Enrique Dans]

*Gracias ;)*

#### Cualquier duda, contactar con el mail de mi perfil: [@gangsthub]
[se compone de]:https://github.com/gangsthub/FiltroAEDE/blob/master/ADPAEDE.txt
[tener instalado *AdBlock Plus* o actualizado (2.0 o superior)]:https://adblockplus.org/es
[tener instalado *uBlock*]:https://chrismatic.io/ublock/
[listado completo]:https://adblockplus.org/en/subscriptions
[@j3j5]:https://github.com/j3j5
[Lista de medios alternativos]:http://wiki.15m.cc/wiki/Lista_de_medios_de_comunicaci%C3%B3n_alternativos
[Artículo]:http://pobre.tk/p/i/c/2-filtro-aede
[Artículo de Enrique Dans]:http://www.enriquedans.com/2014/11/por-que-es-importante-boicotear-los-medios-de-aede.html
[@gangsthub]:https://github.com/gangsthub
