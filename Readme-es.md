# Una guía mucho más breve a [Mastodon](https://joinmastodon.org)

<p style="text-align:center;"><h1>NO SE ASUSTEN.</h1></p>

**Mastodon tiene unas cuantas diferencias importantes con Twitter, pero te acostumbrarás.** Se intentó marcar todas las diferencias importantes con el emoji :bangbang: ; disculpen si faltó alguna. ¡Ni quien escribió esta guía ni el que traduce andan en Twitter desde hace mucho!

Acá se hizo lo posible para que esto sea entendible, ¡pero se agradece cualquier sugerencia! Si tenés cuenta en Github, podés mandar tus pedidos de cambios de forma directa; o si no, podés contactarte con dos personas:

1) Con quien hizo la guía original en inglés [en Mastodon](https://elekk.xyz/@noelle) o por mail en `noelle AT noelle.codes`. 
2) Conmigo que hice esta traducción [en Mastodon](https://social.pueseso.club/@diazepan) o por mail en `juntapuchos AT firemail.cc`

Si vas a copiar un link de esta página, usá este link http://guidetomastodon.com, y acordate de darle crédito a [@Noelle@elekk.xyz](https://elekk.xyz/@noelle). ¡Muchas Gracias!

## Tabla de contenidos

* [¿Qué es Mastodon?](#qué-es-mastodon)
* [¿Qué parecido tiene con Twitter?](#qué-parecido-tiene-con-twitter)
* [¿Qué parecido tiene con el email?](#qué-parecido-tiene-con-el-email)
* [¿Y qué tiene de distinto con ambas; o mejor dicho, qué son las Lineas de tiempo locales y federadas?](#y-qué-tiene-de-distinto-con-ambas-o-mejor-dicho-qué-son-las-lineas-de-tiempo-locales-y-federadas)
* [¿Qué es el Fediverso?](#qué-es-el-fediverso)
* [¿Cómo establezco la presencia de mi marca en Mastodon?](#cómo-establezco-la-presencia-de-mi-marca-en-mastodon)
* [¿Cómo puedo estar verificado en Mastodon?](#cómo-puedo-estar-verificado-en-mastodon)
* [Está bien, ¿Cómo hago para que la gente sepa que yo soy quien dice ser?](#está-bien-cómo-hago-para-que-la-gente-sepa-que-yo-soy-quien-dice-ser)
* [¿COMO ELIJO UNA INSTANCIA?](#como-elijo-una-instancia)
* [Encontré otra instancia que me gusta más. ¿Puedo mudar mi cuenta?](#encontré-otra-instancia-que-me-gusta-más-puedo-mudar-mi-cuenta)
* [¿Cómo cambio mi nombre de usuario?](#cómo-cambio-mi-nombre-de-usuario)
* [¿Cómo menciono a alguien que no está en mi instancia?](#cómo-menciono-a-alguien-que-no-está-en-mi-instancia)
* [¿Cuales son las reglas?](#cuales-son-las-reglas)
* [¿Qué pasa si veo a alguien rompiendo las reglas?](#qué-pasa-si-veo-a-alguien-rompiendo-las-reglas)
* [¿Cuales son los diferentes tipos de toots?](#cuales-son-los-diferentes-tipos-de-toots)
* [¿Cómo funciona la configuración de privacidad?](#cómo-funciona-la-configuración-de-privacidad)
* [¿Qué tan privado es "Privado"?](#qué-tan-privado-es-privado)
* [¿Qué pasa cuando alguien me sigue?](#qué-pasa-cuando-alguien-me-sigue)
* [Así que si hago privada mi cuenta, ¿Sólo la gente aprobada podrá ver mis toots?](#así-que-si-hago-privada-mi-cuenta-sólo-la-gente-aprobada-podrá-ver-mis-toots)
* [¿Qué pasa si alguien está siguiéndome o interactuando conmigo y no quiero que siga haciéndolo?](#qué-pasa-si-alguien-está-siguiéndome-o-interactuando-conmigo-y-no-quiero-que-siga-haciéndolo)
* [¿Cómo sé si alguien me silenció o me bloqueó?](#cómo-sé-si-alguien-me-silenció-o-me-bloqueó)
* [¿Qué pasa si me paso del límite de caracteres?](#qué-pasa-si-me-paso-del-límite-de-caracteres)
* [¿Qué son los hashtags?](#qué-son-los-hashtags)
* [¿Qué significa "CW"?](#qué-significa-cw)
* [Le adjunté una foto a mi toot. ¿Qué es eso de 'marcar como sensible'?](#le-adjunté-una-foto-a-mi-toot-qué-es-eso-de-marcar-como-sensible)
* [Le adjunté una foto a mi toot. ¿Qué es ese botón de editar?](#le-adjunté-una-foto-a-mi-toot-qué-es-ese-botón-de-editar)
* [¿Por qué debería agregarle un texto alternativo a mi foto?](#por-qué-debería-agregarle-un-texto-alternativo-a-mi-foto)
* [¿Cómo es que mi amigo en otra instancia puede usar este emoji y yo no puedo?](#cómo-es-que-mi-amigo-en-otra-instancia-puede-usar-este-emoji-y-yo-no-puedo)
* [¿Por qué no puedo buscar una palabra o frase específica?](#por-qué-no-puedo-buscar-una-palabra-o-frase-específica)
* [¿Por qué no puedo citar un toot?](#por-qué-no-puedo-citar-un-toot)
* [La cultura en Mastodon parece rara, ¿no?](#la-cultura-en-mastodon-parece-rara-no)
* [¿Cual es la etiqueta generalmente aceptada en Mastodon?](#whats-the-generally-accepted-mastodon-etiquette)
* [Me gusta Mastodon pero prefiero la apariencia de Twitter.](#me-gusta-mastodon-pero-prefiero-la-apariencia-de-twitter)
* [Me gusta Mastodon pero quiero usarlo en mi teléfono.](#me-gusta-mastodon-pero-quiero-usarlo-en-mi-teléfono)
* [¿Cómo puedo respaldar mi cuenta de Mastodon?](#cómo-puedo-respaldar-mi-cuenta-de-mastodon)
* [¿Puedo usar el teclado para navegar en Mastodon?](#puedo-usar-el-teclado-para-navegar-en-mastodon)
* [¿Cómo funcionan los favoritos en otros tipos de servidores?](#cómo-funcionan-los-favoritos-en-otros-tipos-de-servidores)
* [Qué raro, mi servidor no tiene muchas de esas cosas.](#qué-raro-mi-servidor-no-tiene-muchas-de-esas-cosas)
* [Qué raro, mi servidor tiene un montón de características extra.](#qué-raro-mi-servidor-tiene-un-montón-de-características-extra)
* [Tengo otras preguntas.](#tengo-otras-preguntas)
* [¿Cómo puedo contribuir a la guía?](#cómo-puedo-contribuir-a-la-guía)

## ¿Qué es Mastodon?

Mastodon es una plataforma de software de redes sociales. Permite que alguien administre su propio sitio de redes sociales (y deje que otra gente lo use también, si quiere), y cada sitio de Mastodon es capaz de comunicarse con todos los otros sitios de redes sociales de Mastodon (y también [algunos otros](https://en.wikipedia.org/wiki/ActivityPub)). Es como una cruza entre Twitter y el email, pero no es exactamente igual a cualquiera de estos.

El nombre Mastodon viene de [la banda de metal de ese nombre](https://www.mastodonrocks.com/), pero su temática viene del animal ya extinto conocido como [Mastodonte (o Mammut)](https://es.wikipedia.org/wiki/Mammut).

## ¿Qué parecido tiene con Twitter?

Allí escribís estados relativamente cortos, y podés ver una lista en constante actualización de los estados de la gente que seguís. Podés tener la notificaciones (respuestas, republicaciones, favoritos, DMs) en una columna separada.

Así como los estados en Twitter se llaman "tweets", los de Mastodon se llaman "toots". Un toot puede tener como mucho 500 caracteres.

Mastodon también soporta hashtags, que son palabras con el prefijo #, como por ejemplo "#software" or "#introduccion". Podés hacer click en un hashtag para buscar otros toots que tienen ese tag.

## ¿Qué parecido tiene con el email?

:bangbang: Cada instancia de Mastodon es independiente pero dentro de una red, como los servidores de correo electrónico. Si te registrás para tener una cuenta de email en gmail.com, no hace falta que tengas una cuenta en hotmail.com o aol.com, pero podés mandar y recibir mensajes desde y hacia usuarios en hotmail.com y aol.com. 

Aquí pasa lo mismo. Si te hacés una cuenta en mastodon.social, no hace falta que te hagas una cuenta en cualquier otra instancia, pero podés conversar con usuarios de otras instancias y estos pueden conversar contigo. 

Podés crearte cuentas en varias instancias si lo que querés es hablar de cosas distintas de forma separada. Por ejemplo una cuenta en https://qoto.org para hablar de ciencia y tecnología, otra en https://mastodon.gamedev.place para hablar de juegos, y otra en https://mastodon.online para charlas en general. Tenés que loguearte en cada cuenta de forma separada y mantenerlas abiertas en ventanas o pestañas separadas. (Todas las aplicaciones móviles también permiten cuentas múltiples.)

**Tené en cuenta que en general, al hablar de Mastodon, "instancia" y "servidor" significan lo mismo.**

## ¿Y qué tiene de distinto con ambas; o mejor dicho, qué son las Lineas de tiempo locales y federadas?

:bangbang: Mastodon tiene dos lineas de tiempo adicionales que podés ver: la Linea de tiempo local y la Linea de tiempo federada.

La Linea de tiempo local se hace con todos los posteos de estado público escritos por los usuarios de tu instancia, salvo las respuestas. (Una respuesta se refiere solo a los toots posteados en respuesta a otro toot - ¡NO a cualquier toot que sólo mencione a otro usuario!)

La Linea de tiempo federada se hace con todos los posteos de estado público escritos por cualquier usuario del cual tu instancia tenga conocimiento, incluso de otras instancias. Tu instancia conoce a un usuario remoto si al menos un usuario de tu instancia lo haya seguido ALGUNA vez.

Las Lineas de tiempo locales y federadas pueden a veces ser chorros de mucha información de lo rápido que van. ¡Ten cuidado!

## ¿Qué es el Fediverso?

~~Desafortunadamente, nada puede decirse sobre qué es el Fediverso~~

El Fediverso es esa gigantesca matriz de servidores que se comunican a través de los protocolos ActivityPub u OStatus. (Hablando en general, a menos de que desarrolles o edites software para interactuar con el fediverso, no necesitás saber qué son esos protocolos.) En el fediverso hay muchos y variados tipos diferentes de software para servidor, por ejemplo Pixelfed, Pleroma, Misskey, o WriteFreely. Entre ellos Mastodon es uno de los más populares, y esta guía es sobre este. Si estás usando alguno de los otros, esta guía quizás no te va a servir mucho.

## ¿Cómo establezco la presencia de mi marca en Mastodon?

:bangbang: Respuesta corta: **De forma extremadamente cuidadosa.**

Hemos llevado quince años de cómo Twitter, Facebook, y quién sabe cuantas otras plataformas de redes sociales se convirtieron en plataformas para la Optimización para motores de búsqueda (o por sus siglas en inglés, SEO), la Conciencia de marca (Brand Awareness), y la Sinergia corporativa, y acá se debe decir con franqueza: LA MAYORÍA DE NOSOTROS ESTAMOS MUY, PERO QUE MUY CANSADOS DE ESO.

Mastodon no se trata de aprovechar a tus seguidores para convertirlos en clientes. No se trata de SEO o lealtad de marca. **Mastodon se trata de gente.** No trates a la gente como clientes potenciales que puedan comprarte lo que vendés; tratalos como la *gente* a quien te gustaría conocer.

Si sos alguien que hace o crea algo y pensás que alguien querría comprar tu producto o usar tu servicio, ¡está bien! Podés contarle a la gente sobre eso - solamente *tratalos como gente*, no como objetivos de marketing.

Hay un comportamiento en que las compañías participan a menudo y que enloquece a la gente, y es algo que *de verdad* no deberías hacer: **no mandes mensajes promocionando tu producto o servicio a nadie y sin que te lo pidan**. Conocé gente, conversá con esa gente, y si pensás que alguien que vos conocés podría estar interesado y no sabe lo que estás haciendo, *entonces* contale lo que hacés o lo que creas.

Si representás a una compañía y tu jefe te dice que tu compañía necesita tener presencia en Mastodon, esto es lo que le podés decir (e incluso podés decirle que yo te dije que se lo dijeras):

> Mastodon no funciona así. Si vamos a tener presencia en Mastodon, debe ser alguien con tiempo para *ser* alguien en esa cuenta, y no un portavoz corporativo. Eso significa que la persona en la cuenta de Mastodon no se va a llevar bien con todo el mundo (aunque debería intentarlo) y va a tratar a los otros usuarios como gente y no como objetivos de marketing. Si está bien así, me encargaré de eso. Si no, tenés que hacer una mayor investigación sobre Mastodon antes de establecer una presencia ahí.

## ¿Cómo puedo estar verificado en Mastodon?

:bangbang: A diferencia de Twitter, Mastodon no tiene incluida la verificación de cuentas. Acá asumimos que sos quien decis ser. Si ves a alguien con un check junto al nombre (tipo :white_check_mark:), simplemente escribieron el emoji junto al nombre y nada más. 

Dicho esto, algunos administradores de instancias requieren pruebas de identidad antes de permitir registrar a un usuario, pero **no cuentes en que eso sea lo normal**.

**Si alguien se hace pasar por vos, contactate con el administrador de la instancia en que está esa persona para resolverlo.**

## Está bien, ¿Cómo hago para que la gente sepa que yo soy quien dice ser?

Las instancias de Mastodon te permiten añadir metadatos a tu perfil - hasta cuatro campos que se muestran en una tabla en tu página de perfil que no cuentan dentro del largo del texto del perfil. Si usás esos campos para enlazar a tus otros sitios web, algunas instancias te dejarán verificar que esos sitios web son *tuyos* al ofrecer un link en esos sitios web que dirijan a tu cuenta en Mastodon. Por ejemplo, si tenés un sitio web personal, podés incluir el link a tu sitio web en tus metadatos de Mastodon, y luego incuir un link a tu cuenta de Mastodon en el header del sitio web, y Mastodon verificará que sos la persona que es dueña de tu sitio web.

Una instancia de Mastodon que permita eso contendrá las instrucciones en la página de **Editar Perfil** sobre como añadir el enlace de verificación.

# ¿COMO ELIJO UNA INSTANCIA?

Las mayúsculas son a propósito.

Elegir una instancia puede ser difícil. Muchas instancias tienen un enfoque específico: `loa.masto.host` es un espacio seguro para gente LGTB+, `infosec.exchange` es un espacio para quienes les gusta la seguridad informática, `mastodont.cat` fue hecha para quienes hablan catalán, y `botsin.space` se enfoca en el desarrollo y alojamiento de bots automatizados. En `oulipo.social` no se permite escribir un toot que incluya la letra "e". 

Si no te creaste una cuenta en mastodon todavía, te podría ser útil probar en una de las instancias más grandes, como `mastodon.social` - la instancia principal, con más de 100.000 usuarios activos - o `mas.to` . Estas instancias tienen una población enorme y generalmente amigable que te ayudarán a encontrar una instancia más de nicho si eso es lo que estás buscando. Sin embargo, cuidado, porque debido a su tamaño, las lineas de tiempo locales en esas instancias pueden moverse *muy* rápido.

(*Una breve nota sobre mastodon.social: Esta **es** la instancia más grande de propósito general. Mucha gente va allí y nunca vuelve a buscar otras instancias. Si te hacés una cuenta en mastodon.social, considerá tratarla como una parada temporal mientras buscás una instancia que se adecúe más a tus necesidades e intereses. Una vez que la encuentres, podés exportar a toda la gente que seguís, silenciás y bloqueás en mastodon.social e importarlos a tu nueva cuenta, así no tenés que buscar a todos de nuevo.*)

Si ya te registraste en una instancia pero no estás seguro de si te sirve, intentá preguntar por allí si hay instancias que te podrían servir más. También, intentá buscar por un #hashtag que te interese; si ves a mucha gente en una instancia hablando de esa cuestión, puede que sea un buen lugar para que revises.

También podés probar el selector de instancias en [joinmastodon.org](https://joinmastodon.org/communities) o el asistente [instances.social](https://instances.social/), aunque estos tienen *muchas* instancias listadas y puede que te abrumes. Hacelo despacio y con calma.

## Encontré otra instancia que me gusta más. ¿Puedo mudar mi cuenta?

Sí y no.

Hay dos maneras de lograr esto: podés **redirigir** tu cuenta o **migrar** tu cuenta.

Si **redirigis** tu cuenta, tu cuenta vieja tendrá una noticia de redirección añadida, y no podrás volver a usarla por completo (Creo que esto significa que no podrás postear toots desde esa cuenta). Igual podrás exportar los datos de tu cuenta, y podrás reactivar tu cuenta en cualquier momento. A los usuarios que van al perfil de tu vieja cuenta se les contará que te pueden encontrar en tu cuenta nueva. Nada más se transferirá automáticamente. Podés hacerlo yendo a `[tu servidor]/settings/migration/redirect/new` (por ejemplo, elekk.xyz/settings/migration/redirect/new). También hay un link en la página de migración de cuentas. Todo lo que tenés que hacer es colocar el nombre de la cuenta a la que estás redirigiendo y Mastodon hará el resto.

(Podés mudar manualmente una buena parte de tu información si redireccionás tu cuenta. Ver los pasos 4-6 más abajo.)

Si **migrás** tu cuenta, pasarán las mismas cosas que si redirigís tu cuenta. **Además**, todos tus seguidores se moverán a tu nueva cuenta (para que nadie tenga que buscarte y volverte a seguir). *Podés*, además, mudar manualmente tus seguimientos, listas, usuarios bloqueados, silenciados, dominios bloqueados, y marcadores, pero el sistema no lo hará de manera automática.

**En ninguno de los casos se mudarán tus toots. Estarás empezando con un historial vacío de toots en tu nueva cuenta.**

Estos son los pasos para **migrar** tu cuenta, incluyendo pasos adicionales. (Parecen muchos pasos, pero se dividieron algunas cosas para que las instrucciones sean más fáciles de seguir.)

1. Creá tu cuenta **nueva**. Esto puede hacerse en la misma instancia en la que estás, o en otra instancia.
2. En tu cuenta **nueva**, hacé click en `Preferencias` en el panel de la derecha, luego a `Perfil > Apariencia`. Debajo de la imagen de cabecera y el avatar, asegurate de que **Hacer privada esta cuenta** *no esté marcado*. (Si está marcado, tendrás que aprobar manualmente cada seguidor que el proceso automatizado intente traer.) Hacé click en **Guardar Cambios** en la parte de arriba o abajo de la página si tuviste que desmarcar la opción.
3. En tu cuenta **nueva**, en Preferencias, andá a `Cuenta > Ajustes de la cuenta `. En la parte de abajo de la página, bajo el encabezado `Migrar de una cuenta diferente` , hacé click en "**crear un alias de la cuenta**".
4. Escribí el `nombredeusuario@instancia` de la cuenta **vieja** (por ejemplo, `noelle@elekk.xyz`) y hacé click en "**Crear Alias**".
5. (Opcional) En tu cuenta **vieja**, en Preferencias, andá a `Importar y exportar > Exportar información`.
6. (Opcional) Verás una lista de... ¿estadísticas de la cuenta, quizás? Junto a "Sigue", "Listas", "Personas que has bloqueado", "Tienes en silencio", "Bloqueos de dominios", y "Marcadores", verás un :arrow_down:`CSV`. Hacé click ahí por cada cosa que quieras mudar a tu cuenta nueva; esto descargará una lista de esas cosas en un formato estandar. Hacé una nota de endonde se descargan.
7. (Opcional) En tu cuenta **nueva**, en Preferencias, andá a `Importar y exportar > Importar`. Para cada uno de los archivos que descargaste (salvo las listas, las cuales no tienen una función para importar todavía):
  * Usá el menú desplegable de arriba (debajo de `Importar tipo`) para seleccionar lo que querés importar.
  * Debajo de `Información`, hacé click en el botón de "**Examinar...**" para que abra el selector de archivos, y selecciones el archivo CSV que acabás de descargar.
  * Seleccioná "**Unir**", si no está seleccionado.
  * Click en "**Cargar**".
8. En tu cuenta **vieja**, en Preferencias, andá a `Cuenta > Ajustes de la cuenta `. Al fondo de la página, bajo el encabezado `Mudarse a otra cuenta`, hacé click en "**configurarlo aquí**".
9. Escribí el `nombredeusuario@instancia` de la cuenta **nueva**, junto con la contraseña de la cuenta **vieja**. Esto verifica que sos el dueño de la cuenta (en caso de que te olvides de desloguearte y otro use la computadora). Y luego hacés click en "**Migrar Seguidores**".

¡Y ya está! Notá por favor que puede tomar un rato migrar todo e importar todo lo que hayas subido, especialmente si te mueves desde o hacia un servidor grande o viejo.

:bangbang: **Importante**: Este proceso es lo más cercano que Mastodon tiene de cambiar el nombre de usuario.

¡Agradecimientos a [Ted](https://peoplemaking.games/@esdin) y arachnomyrmex que ayudaron en que esto sea claro!

## ¿Cómo cambio mi nombre de usuario?

:bangbang: Versión corta: no podés. Una vez que elegís el nombre de usuario de tu cuenta, no se puede cambiar, así que elegí con cuidado.

Versión larga: La única manera de cambiar el nombre de usuario es migrando la cuenta (ver más arriba), pero de nuevo, esto no muda los toots de una cuenta a la otra. 

Algunos administradores intentaron cambiar el nombre de usuario directamente en la base de datos (a pedido de los usuarios), y por alguna razón, al hacerlo se rompe la federación para esa cuenta; y no pueden mandar ni recibir mensajes a otras instancias ni recibir menciones.

## ¿Cómo menciono a alguien que no está en mi instancia?

:bangbang: Los nombres de usuario en Mastodon tienen la forma @*nombredeusuario*@*instancia*. Por ejemplo quien hizo esta guía en inglés tiene su cuenta en mastodon.social y es @<span>noelle</span>@mastodon.social; y tambien tiene una en elekk.xyz y es @<span>noelle</span>@elekk.xyz. Si estás mencionando a alguien en una instancia diferente, tenes que escribir toda la dirección (aunque el cuadrito donde escribís el toot te ayudará a autocompletar el nombre de usuario si es un nombre que la instancia ya conoce). 

Si estás mencionando a alguien de tu propia instancia, sólo necesitás escribir la primera parte; si estás en mastodon.social, @Gargron te llevará a contactar con él de la misma forma que @<span>Gargron</span>@mastodon.social. Si omitís el "@*instancia*" Mastodon entiende que le querés hablar al usuario local.

## ¿Cuales son las reglas?

Las reglas dependen de la instancia en que estés. Cada instancia tiene una página en https://<span>*instancia*</span>/about/more que por lo general contiene más información sobre la instancia y a menudo describe las normas de la comunidad. Por ejemplo, mastodon.social tiene las normas de su comunidad escritas en https://mastodon.social/about/more .

Tené presente que estas son normas en general y no reglas estrictas. Como cada instancia es administrada por un grupo separado de moderadores - ¡a menudo suele haber un solo moderador! - ellos tienen la última palabra sobre qué se permite y qué no se permite en sus instancias. Los administradores de tu instancia incluso pueden llegar hasta bloquear una instancia entera si sus usuarios resultan incompatibles con los valores que defiende tu instancia y los moderadores de la otra instancia no ayudan.

## ¿Qué pasa si veo a alguien rompiendo las reglas?

Si ves a alguien que rompe las reglas, podés reportarlo. Hacé click en la parte `...` que aparece debajo del toot que rompe la regla, y seleccioná dentro del menú `Reportar`. Eso mostrará una ventana donde podés elegir otros toots recientes de ese usuario, si es necesario, y también escibir una *razón* para reportarlo, para que el moderador que reciba el reporte entienda por qué se lo mandaste. 

Si el usuario es de otra instancia, debajo de las razones del reporte, aparecerá un switch para "Reenviar a *su instancia*". Esto no solo reporta el usuario a los moderadores de tu instancia, sino que también manda el reporte a la instancia del otro usuario. Antes de hacer eso, **comprobá las reglas de la instancia en la que el usuario está**. Puede que no esté rompiendo sus reglas.

**Los moderadores y administradores de *tu* instancia podrán ver que vos mandaste el reporte. Si enviás el reporte a la instancia de un usuario remoto, los moderadores y administradores de esa instancia *no* podrán ver quién envió el reporte — sólo podrán ver que vino desde tu instancia.**

Por defecto, no te llegarán notificaciones sobre las acciones que los moderadores y administradores tomen en respuesta a tu reporte. Podés preguntarles, pero que no te extrañe si te responden "no hacemos comentarios sobre como resolvemos los reportes".

## ¿Cuales son los diferentes tipos de toots?

:bangbang: Los toots de Mastodon (y de otros servidores del fediverso) pueden encadenarse de diferentes maneras. Se pueden usar estos tres términos para referirse a los tipos diferentes de toots. Puede que otra gente use otros términos.

* Los **toots sueltos** son toots que no son respuestas a ningún otro toot. (O sea, no hiciste click en el botón de responder para escibir el toot.) Estos están al principio de la cadena. Podés incluir los nombre de usuarios de otra gente en los toots sueltos para mencionarlos; hacer eso no hace que el toot sea una respuesta. **Por ejemplo:** Vos usás el cuadrito (El que dice "¿En qué estás pensando?") para hacer un toot nuevo.
* Las **autorespuestas** son toots que son respuestas directas a *uno de tus propios* toots sueltos o a otra autorespuesta. De nuevo, estas pueden incluir referencias a otra persona. Podés seguir respondiendo tus propios toots lo más que quieras, y *mientras un toot de otro no esté encima de lo que estés escribiendo en la cadena*, seguirán siendo autorespuestas. **Por ejemplo:**  Vos hacés click en el botón de responder en uno de tus propios toots sueltos para responderte a ti mismo, y luego haces click en responder a *ese* toot para responderte de nuevo.
* Las **respuestas** son toots que son respuestas a los toots de otra perona *o respuestas a una respuesta de otra persona*. **Por ejemplo:** Hacés click en el botón de respuesta del toot de otra persona para responderle, **o** hacés click en el botón de respuesta de un toot tuyo que sea la respuesta a un toot de otra persona.

[Aquí](replies.png) tenés un diagrama para ver mejor (es un link porque es una imagen grande). Vas a ver que apenas entre en la cadena un toot de otra persona, tus respuestas dejan de ser autorespuestas. Esto es importante, porque las autorespuestas y las respuestas funcionan distinto en las lineas de tiempo de tus seguidores.

## ¿Cómo funciona la configuración de privacidad?

Debajo del cuadrado para escribir toots, verás unos íconos: entre ellos está uno que puede ser un planeta o un candado. Hacés click ahi y con eso elegis configurar la privacidad de ese toot que vas a escribir. *Podés elegir el nivel por defecto de privacidad en la parte de **Preferencias > Otros > Privacidad de publicaciones**.*

* **Público** significa que todos pueden ver el toot. Aparecerá en tu lista de toots y en las lineas de tiempo principales de tus seguidores. Tus *toots sueltos* y *autorespuestas* que sean públicas aparecerán en tu lista de toots, en las lineas de tiempo principales de tus seguidores, en las lineas de tiempo locales y federadas, y en las menciones de cualquiera a quien menciones por su nombre de usuario. Tus *respuestas* públicas aparecerán en tu lista de *toots y respuestas* (*no* en la lista principal de toots; ¡es una lista separada!), en las lineas de tiempo principales de cualquier seguidor tuyo que *también* siga a esa persona a la que seguís, y en las menciones de cualquiera a quien menciones por su nombre de usuario.
* **No listado** significa que todos pueden ver el toot, pero no aparecerá en las lineas de tiempo públicas - tanto la Local como la Federada. Aparte de eso, los toots no listados se comportan de la misma manera que los toots públicos.
* **Solo seguidores** significa que sólo la gente que te sigue y la gente que mencionaste en el toot puede ver el toot en sus lineas de tiempo o en tu página de perfil. Si alguien que no te sigue ve tu perfil, no verá tus posts que son solo seguidores. *Para tus seguidores*, los toots solo seguidores se comportan de la misma manera que los toots no listados. **Tus toots solo seguidores que mencionen a otro usuario también aparecerán en las menciones de ese usuario, ¡incluso si no te sigue!**
* :bangbang: **Solo cuentas mencionadas** significa eso exactamente; que sólo la gente mencionada en tu toot pueden verlo, y **cualquiera** que sea mencionada puede verlo (a menos de que te haya bloqueado o silenciado). Aparecerán en sus menciones y, en los servidores de Mastodon por encima de la versión 3.0, aparecerán en la columna de Mensajes Directos.

Tené presente que algunos servidores, que corren un software distinto pero compatible con el de Mastodon, ignorarán esas configuraciones de privacidad si les mandás un mensaje a esos usuarios, ¡así que tené cuidado!

## ¿Qué tan privado es "Privado"?

Esto no se puede enfatizar lo suficiente: **Los toots que son solo cuentas mencionadas (DMs) NO están cifrados ni son seguros.**

El administrador de tu servidor puede leer *cualquier* toot escrito en tu servidor, como también *cualquier* toot enviado a otro usuario en tu servidor. **Sin embargo**, es bastante difícil hacerlo. Tus toots privados no aparecerán en el panel de administrador del sitio; tu administrador tiene que acceder manualmente, directamente a la base de datos -- normalmente logueándose a la linea de comandos del servidor -- para poder acceder a estos. No es algo que los administradores hagan por capricho; sólo lo hacen cuando están obligados a hacerlo, y esta es la razón:

Esta es una precaución necesaria de seguridad. Los administradores *no quieren* leer tus toots privados, pero tienen que ser *capaces* de hacerlo porque si no los toots privados permiten que ciertos usuarios puedan acosar a otros en secreto o llevar a cabo acciones ilegales sin el conocimiento del administrador, y bajo varias leyes el administrador será considerado responsable por permitir el acoso o el comportamiento ilegal *incluso si ellos no sabían que esto ocurría*.

Dicho esto, en general, tu administrador sólo revisará tus toots marcados como solo cuentas mencionadas si tienen una razón para creer que está ocurriendo un caso de acoso o de acciones ilegales. Asegurate de que confiás en que tu administrador actúe de esa manera, y si no, puede ser un buen momento para buscar otra instancia.

Siguiendo con la cuestión, hay que mencionar que esto ocurre en casi todas las redes sociales. Los administradores de Twitter pueden leer tus DMs. Los administradores de un foro pueden leer tus mensajes privados. No es una novedad ni una característica inusual de Mastodon; Sólo queremos asegurarnos de que lo sepas.

**Como regla general, si una aplicación que usás no está [cifrada de extremo a extremo](https://es.wikipedia.org/wiki/Cifrado_de_extremo_a_extremo), la información que estás mandando no está segura a menos de que tomes [medidas extra por fuera de la aplicación para asegurarla](https://es.wikipedia.org/wiki/Pretty_Good_Privacy).**

## ¿Qué pasa cuando alguien me sigue?

~~Si alguien te sigue, sufrirás una deuda vitalicia hacia esa persona. Se te pedirá que sacrifiques tu vida por esa persona cuando esta lo requiera. Una vez que hayas hecho eso, te dejará de seguir y, si has sobrevivido, eres libre de seguir con tu vida normalmente.~~

Nah, es joda.

Si alguien te sigue, verá tus toots en su linea de tiempo principal y podrá ver tus toots que son solo seguidores. Si querés, podés limitar a la gente que puede seguirte haciendo click en **Editar perfil** y seleccionar **Hacer privada esta cuenta**, lo cual te permitirá aprobar y rechazar manualmente a la gente que quiera seguirte.

## Así que si hago privada mi cuenta, ¿Sólo la gente aprobada podrá ver mis toots?

Sí y no.

Con la cuenta puesta en privado, podés aprobar a quienes pueden seguirte *a través de la interfaz de Mastodon*. Eso significa que sólo la gente que apruebes podrá ver tus toots de **solo seguidores**. Tus toots **no listados** seguirán apareciendo en tu perfil, y tus toots **públicos** aparecerán tanto en tu perfil como en las lineas de tiempo locales y federadas.

**Sin embargo.**

:bangbang: Todas las cuentas de Mastodon (en un servidor no modificado) también crean una fuente RSS de sus toots públicos y no listados - p.e. los toots que aparecen en el perfil de la cuenta. No incluye los toots de solo seguidores ni los mensajes directos, y si le [pusiste un CW a un toot](#qué-significa-cw), sólo el CW aparece en la fuente RSS, no lo que está debajo. 

Tu fuente de RSS aparece en `https://<your-server>/users/<your-username>.rss` ; por ejemplo, como estoy en `https://social.pueseso.club/@diazepan`, mi fuente de RSS es `https://social.pueseso.club/users/diazepan.rss` . (¡Acordate de quitarle el `@`!)

**Todos pueden suscribirse a esas fuentes usando un lector de RSS para ver tus toots públicos y no listados cuando los posteás.** No podés controlar quien puede ver esas fuentes, pero no contienen (y, por diseño, no pueden contener) tus toots de solo seguidores o mensajes directos. *Si sólo escribís toots que son solo para seguidores, tu fuente de RSS estará vacía.*

Recordá, podés elegir el nivel por defecto de privacidad para tus toots en la parte de **Preferencias > Otros > Privacidad de publicaciones**. Si tenés una cuenta puesta como privada, probablemente preferirás elegir por defecto que tus toots sean de solo seguidores para que tengas que hacer un esfuerzo activo para hacer un toot público o no listado.

## ¿Qué pasa si alguien está siguiéndome o interactuando conmigo y no quiero que siga haciéndolo?

Acá tenes unas opciones.

* **Si lo único que querés es que no aparezca en tus lineas de tiempo**, podés *silenciarlo*. Esto evitará que sus toots aparezcan en tus lineas de tiempo; podés incluso bloquear las notificaciones (Favoritos, retooteos y menciones) de ese usuario, por ende si no querés ver los toots sueltos de alguien pero sí querés ver sus intentos de interactuar contigo, podés hacer eso.
* **Si no querés ver a ese usuario y tampoco querés que te vea**, podés *bloquearlo*. Esto automáticamente lo silenciará; si te estaba siguiendo y/o lo estabas siguiendo, cortará esas relaciones también. El usuario no será capaz de seguirte o de aparecer en *ninguna* de tus lineas de tiempo a menos que lo desbloquees. (Ver el sin embargo más abajo.)
* **Si te está acosando o está rompiendo las reglas**, podés [reportarlo](#qué-pasa-si-veo-a-alguien-rompiendo-las-reglas), y con suerte, tu moderador se encargará de eso.

Todas esas tres opciones están disponibles haciendo click en la parte `...` que aparece debajo del toot del usuario o en su perfil dentro de la interfaz web de Mastodon.

**Sin embargo.**

Al igual que con una [cuenta privada](#así-que-si-hago-privada-mi-cuenta-sólo-la-gente-aprobada-podrá-ver-mis-toots), cualquier usuario — incluso los que has bloqueado o que hayan sido suspendidos por un moderador — pueden ir a tu página pública o tu fuente de RSS para ver toots públicos y no listados. No hay una buena manera de evitar eso desafortunadamente, salvo hacer que todos tus toots sean solo para seguidores.

## ¿Cómo sé si alguien me silenció o me bloqueó?

No vas a recibir una notificación si alguien te silencia o te bloquea.

Si alguien te silenció, no hay manera de que te enteres. Si no te responde consistentemente cuando lo mencionás, podés tener sospechas, pero Mastodon deliberadamente hace que te sea casi imposible saber si te han silenciado. (Entre otras cosas, es un recurso temporal para tratar de evitar que alguien te acose creando varias cuentas para esquivar los silenciamientos.)

Si alguien te bloqueó, ya no podrás seguirlo, sus toots no aparecerán en tu linea de tiempo, y cuando veas el perfil de su cuenta *dentro de la interfaz web de Mastodon*, ninguno de sus toots cargarán. (Vale notar que si estás mirando el perfil de alguien que *no* seguís, a veces sus toots no cargarán y es solo porque el servidor está lento, no porque te haya bloqueado, así que no seas *tan* rápido para asumir algo.)

Si alguien te bloqueó, *podés* igual ir a su página pública y ver sus toots públicos y sin listar; los perfiles públicos no necesitan autenticación (o sea, no necesitás estar logueado en esa instancia para verlos) y por ende no pueden saber quien sos ni que el usuario te bloqueó. **Habiendo dicho esto**, seamos honestos. Si alguien te bloqueó, no te quiere cerca. *Podés* seguir leyendo sus toots públicos y sin listar, pero ¿quizás no conviene? En una manera sustancial estás invadiendo su privacidad y cruzando deliberadamente un límite que marcó, y eso de que "el software me lo permite, por lo tanto se puede" es una justificación muy poco sólida. En resumen, dejalo solo.

## ¿Qué pasa si me paso del límite de caracteres?

No te preocupes. En primer lugar, no podés pasarte; Mastodon no te dejará postear un toot con más caracteres que el límite de la instancia. No vas a meterte en problemas ni nada.

Si resulta que lo que querés decir es demasiado largo como para caber en un solo toot, o si pensás en algo más después de postear el toot, podés *responder a tu propio toot*. Soporta hilos de toots, así que podés tootear tantas veces como quieras, respondiendo a cada toot en secuencia, y toda la serie aparecerá cuando alguien haga click en cualquiera de los toots del hilo.

Así que si tu toot es muy largo, dividilo en partes y hacé que una parte sea una respuesta de la parte anterior; si pensás en otra cosa después, respondé al toot original y la respuesta aparecerá cuando alguien haga click en el toot original.

## ¿Qué son los hashtags?

Para hacer un hashtag, escribí "#" y luego una serie de letras o números. Los acentos cuentan; puntuaciones, espacios, símbolos, y emojis no. #buenosdiasloprimero es un hashtag válido; #büénòsdĩǎslŏprįmèrö también; sin embargo #buenos-dias-lo-primero no (solo queda en #buenos).

Un hashtag es un metadato sobre tu toot: provee información adicional que no necesariamente pertenece al cuerpo del toot, pero que es útil para entenderlo. Si sos programador, es casi como un comentario en el código.

Como bonus†, los hashtags son rastreados por cada instancia. Hacer click en un hashtag te dirige a una lista de toots públicos con ese hashtag. Podés usarlos por ejemplo para seguir discusiones de #política, ver gente nueva que llega a Mastodon en #introducción, o seguir las obras hechas por los usuarios en #mastoart.

No exagerés con los hashtags. Como norma, tus hashtags probablemente no deberían ocupar más del 10% del largo total de tu toot. Si exagerás con eso, puede que estés intentando hacer demasiadas cosas a la vez.

† *Esta era la intención original de los hashtags, pero el uso cambió desde ese entonces.*

## ¿Qué significa "CW"?

:bangbang: CW significa Content Warning (Aviso de contenido). Lo que hace es el ocultar el texto de un toot debajo de otro texto (el cual podés elegir); es como un enlace al estilo Leer Más.

Hay gente que usa CWs para hablar de:

* Política
* Sexo
* Cuestiones de mal gusto
* Fobias comunes, como arañas o sangre
* Discusiones sobre salud, tanto física como mental
* Remates para chistes
* Toots largos que de otra manera llenarían las lineas de tiempo de otra gente
* Comentarios sobre discusiones que ocurren en otros lugares del fediverso
* Contacto visual (eso se usa generalmente cuando se suben fotos)

En general, hacé uso de tu sano juicio; Pensá seriamente si hay alguna razón de que alguien no quiera ver esto. Si la hay, usa CW y vas a evitar molestias innecesarias.

**Una nota importante:** Mastodon *no* rastrea hashtags dentro del texto de un CW. Mastodon *sí* rastrea hashtags que están *bajo* un CW. Siempre poné tus hashtags en el cuerpo del toot, nunca en el aviso de contenido.

## Le adjunté una foto a mi toot. ¿Qué es eso de 'marcar como sensible'?

:bangbang: Si marcás tu foto como sensible, la foto quedará oculta detrás de una capa de "Contenido sensible". Esto conviene por ejemplo con fotos que contienen desnudos, violencia gráfica, etc.

Notarás que si tenés una imagen y un CW en un toot, la capa de "Contenido sensible" se prende automáticamente y no puede apagarse. Es a propósito.

## Le adjunté una foto a mi toot. ¿Qué es ese botón de editar?

:interrobang: Cuando adjuntás una imagen, vas a ver un botón de "Editar" (con un ícono de lápiz) en la esquina superior derecha de la imagen. Al haceer click ahí se abre una caja de diálogo que te permite determinar qué parte de la imagen debe verse en en la vista previa; también te permite colocar un texto alternativo para la imagen, el cual la gente puede leer si coloca el mouse sobre el texto, y el cual los lectores de pantalla (los cuales son usados por usuarios con discapacidad visual) pueden leer en vez de decir "imagen embebida".

Para imágenes que mayormente son textos (por ejemplo, una captura de pantalla de un post de Tumblr), Mastodon tiene incorporado un reconocedor óptico de caracteres (OCR) y a menudo puede transcribir la imagen, aunque probablemente deberías revisar la transcripción para asegurarte de que sea precisa. Si, por alguna razón, no funciona el OCR de tu instancia, podés usar una herramienta online como [Online OCR](https://www.onlineocr.net) para transcribir tu imagen. Y si todo eso falla, hay Bots OCR en el fediverso que responderán a tu post con una transcripción si los @mencionás.

El texto en la caja de descripción tiene su propio límite de 1500 caracteres; ¡y **no** cuentan como parte del límite de caracteres del toot!

## ¿Por qué debería agregarle un texto alternativo a mi foto?

En una palabra: Accesibilidad. 

Hay gente en Mastodon que tiene discapacidad visual y usan lectores de pantalla. Hay otros en Mastodon que tienen las imágenes apagadas para reducir el consumo de datos. También pueden ocurrir errores con los discos duros o los servidores, o que el administrador decida borrar archivos viejos, y que tu imagen ya no se cargue más. Agregarle un texto alternativo a una foto permite que la gente en esas condiciones participen en tus toots con todo el contexto.

También podés usar los textos alternativos para agregar chistes extra (como ocurre con los webcomics) o dar un comentario adicional a la imagen. Aprovechá que las descripciones tienen su propio límite de caracteres y escribí lo que quieres.

## ¿Cómo es que mi amigo en otra instancia puede usar este emoji y yo no puedo?

:bangbang: :bangbang: Cada instancia puede definir emojis personalizados para que sus usuarios los usen, y muchas lo han aprovechado. El administrador de tu instancia puede copiar los emojis que le gustan desde otras instancias. Si ves un emoji que te gusta y no está disponible en tu instancia, pedíle a tu administrador que lo copie para allí.

## ¿Por qué no puedo buscar una palabra o frase específica?

Es una herramienta contra el acoso. Los acosadores a menudo buscan palabras o frases en particular (como "TERF" u "homofóbico" o "todes") para venirse encima y atacar a la gente con la que están en desacuerdo. Al limitar la búsqueda sólo a nombres de usuarios y hashtags, Mastodon permite a los usuarios decidir como quieren que sus toots aparezcan en las búsquedas de otros. (Aunque alguna instancias de Mastodon *permiten* búsqueda de texto, sólo podés buscar tus propios toots en esas instancias. Eso te facilita encontrar algo que escribiste hace un rato sin exponerte al acoso.)

## ¿Por qué no puedo citar un toot?

:bangbang: Al igual que con la búsqueda, es otra herramienta contra el acoso. Si querés responder el toot de alguien, tenés que responder a ese toot; no podés retransmitir ese toot a tus seguidores y agregarle un comentario sarcástico.

*(Ni siquiera intentes esquivar eso haciendo una captura de pantalla del toot y adjuntarlo como una imagen. **Podés** hacerlo, pero la comunidad de Mastodon tiende a ver eso de mala manera y si seguís haciendolo vas a conseguir una mala reputación bastante rápido.)*

## La cultura en Mastodon parece rara, ¿no?

¡Puede serlo! Pero suele ser una rareza cómoda

Estos son ejemplos de rarezas comunes (en la comunidad hispanohablante):

* Joseos: Se refiere a la práctica de copiar el texto de un toot, alterar mínimamente su contenido (añadiendo, quitando o modificando palabras) con fines cómicos y postearlo (y opcionalmente retootear el toot original). No se sabe a ciencia cierta el origen del nombre, aunque su establecimiento se remonta a la llegada de usuarios españoles en octubre del 2018. La opinión sobre los joseos está dividida. Por un lado hay muchos usuarios, moderadores y administradores que lo consideran una diversión sana y por otro hay instancias que lo prohiben o que lo restringen a que se haga solo de forma local.
* Fotocachos: Así le dicen a las fotos que se toman los usuarios de sus partes corporales. Generalmente vienen marcadas como material sensible y acompañadas de un hashtag. Hay que insistir en que esta **muy mal** visto descargarse los fotocachos de otros y resubirlos, así que evitá hacerlo.

Ya te vas a acostumbrar.

## ¿Cual es la etiqueta generalmente aceptada en Mastodon?

No hay reglas estrictas para todos, y (como se mencionó antes) diferentes instancias tienen diferentes normas. Dicho esto, muchos siguen unas normas simples para hacer que Mastodon sea un lugar más amigable para todos.

* Si añadís una imagen a un toot pero no lo describís en el toot, usá [un texto alternativo](#le-adjunté-una-foto-a-mi-toot-qué-es-ese-botón-de-editar) para describir la imagen para que la gente que usa lectores de pantalla lo puedan entender.
* Si añadís una imagen que contiene **desnudos, pornografía o contenido sexualmente sugerente, gore, violencia, o política**, o algo que desate desordenes de ansiedad o traumas (como comida, arañas, contacto visual, etc.), [marcalo como sensible](#le-adjunté-una-foto-a-mi-toot-qué-es-eso-de-marcar-como-sensible).
* Si el *texto* de tu toot habla de alguno de esos temas, [usá un aviso de contenido](#qué-significa-cw).
* No necesitás usar un acortador de URLs. Mastodon asume que todas las URLs tienen 20 caracteres de largo. Dejá que la gente vea a donde dirige el link.
* Si hacés un bot que hace posteos automáticos, hacelo que postee con el nivel de privacidad [no listado](#cómo-funciona-la-configuración-de-privacidad). Eso evita que tu bot sea marcado como spam.
* Si usas un script para hacer cross-posting con Twitter (y así postear tus tweets en Mastodon), configurá el script para que use CWs. Eso evita que los temas sensibles (ya mencionados) se pasen de Twitter a Mastodon.
* Ya que hablamos de cross-posting, otra cosa que **no es nada bienvenida** es usar la cuenta de Mastodon para repetir tweets y nada más, ni siquiera interactuar con otros usuarios. Eso también se ve como spam.
* Si ves una conversación y tienes algo para comentar allí:
    * Hacé click en la conversación y asegurate de que lo que queres decir no se haya dicho antes por otro. 
    * Asegurate de que el comentario sea acorde al tono de la conversación, así sos amable con los otros posteadores de la conversación y le da a los demás el beneficio de la duda.
* Recordá que si alguien no te responde, no significa que te ignore. Puede que esté lejos de Mastodon; puede que tenga tantas notificaciones que no haya visto tu toot; puede que haya silenciado la conversación, así que tu respuesta no siguiera apareció. Hay muchas razones por las que alguien se pierde un toot, incluso si está dirigido a ese alguien; no te lo tomes como algo personal.

## Me gusta Mastodon pero prefiero la apariencia de Twitter.

Podrías aprovechar a usar [Pinafore](https://pinafore.social/), una interfaz para Mastodon hecha por [Nolan Lawson](https://toot.cafe/@nolan).

[Halcyon](https://notabug.org/halcyon-suite/halcyon) es u cliente web para Mastodon que replica la interfaz de Twitter. Como Halcyon en sí es software libre y de código abierto, hay [varios servidores que lo usan](https://notabug.org/halcyon-suite/halcyon#instances); podés elegir el que quieras. Usas tu cuenta de Mastodon cuando usas Halcyon; por ejemplo, si tenés cuenta en elekk.xyz, podés usar `tucuenta@elekk.xyz` y la contraseña de allí para loguearte.

Recordá que Pinafore y Halcyon son clientes de terceros, ¡y asegurate de que confíes en ellos antes de darles tu información de sesión!

## Me gusta Mastodon pero quiero usarlo en mi teléfono.

Mastodon tiene un diseño adaptable, así que podés usarlo en el navegador del teléfono. Alternativamente, hay muchas apps disponibles para Mastodon que las podés encontrar [acá](https://joinmastodon.org/apps) entre ellas aplicaciones oficiales [para iOS](https://apps.apple.com/us/app/mastodon-for-iphone/id1571998974) y [para Android](https://play.google.com/store/apps/details?id=org.joinmastodon.android).

## ¿Cómo puedo respaldar mi cuenta de Mastodon?

[Alex Schroeder](https://octodon.social/@kensanata) tiene hecho este [Archivador de Mastodon](https://github.com/kensanata/mastodon-backup/) que te ayudará a respaldar tu cuenta y mucho más.

## ¿Puedo usar el teclado para navegar en Mastodon?

En la interfaz web, sí. Los atajos en la interfaz web se explican en `https://<tu-servidor>/web/keyboard-shortcuts` , a la cual podés acceder cuando estás logueado en la interfaz web. (Podés encontrar el enlace al fondo de la columna **Primeros pasos**, con la etiqueta "Atajos".)

## ¿Cómo funcionan los favoritos en otros tipos de servidores?

En general:

* Si le das click a 'favorito' en un post de otro tipo de servidor (Misskey, Pleroma, GNU Social, etc.) federará apropiadamente. Algunos de estos servidores permiten emojis múltiples de respuestas, y cada uno de ellos selecciona un emoji genérico de "favorito", el cual aparecerá en el post del recipiente.
* Si alguien en un tipo de servidor distinto selecciona un emoji para responder a tu toot, este federará hacia vos en Mastodon como un favorito, *sin importar qué emoji sea*.

## Qué raro, mi servidor no tiene muchas de esas cosas.

¡Puede que no estés en Mastodon! El Fediverso - la gigantesca colección de servidores conectada por los protocolos ActivityPub/OStatus - tiene un montón de tipos distintos de servidores allí. ¡Tu servidor puede que esté usando Pleroma, Misskey, GNU Social, u otra cosa! Desafortunadamente, no sé mucho de ellos, así que tendŕas que preguntar a sus usuarios por una guia como esta.

## Qué raro, mi servidor tiene un montón de características extra.

Como [Mastodon es de código abierto](https://github.com/mastodon/mastodon), podés hacer una copia del código y hacerle todos los cambios que quieras. Y algunos decidieron hacer públicos sus cambios; una de las versiones editadas más populares de Mastodon es [Mastodon Glitch Edition](https://glitch-soc.github.io/docs/), o "glitch-soc". (Se llama así, según yo sé, porque viene de la instancia [glitch.social](https://glitch.social). Glitch-soc tiene varias características extra que los usuarios aprecian a menudo, como la capacidad de usar Markdown en toots y la opción de hacer que un toot solo aparezca en la instancia local pero que no federe a otros servidores.

## Tengo otras preguntas.

¡Preguntá! La gente está generalmente feliz de responder preguntas y ayudar. También, podés beneficiarte de mirar una de estas guías, que tienen una perspectiva distinta:

* [FediThing](https://tech.lgbt/@FediThing) tiene [este sitio web](https://fedi.tips/).
* [Ted](https://peoplemaking.games/esdin) tiene [un documento de tips y FAQ](https://docs.google.com/document/d/1gln7Lg92Vz3TbIjz6qZkpdPOxDAe63jof5snpR4xAa0/).
* [elilla](https://transmom.love/@elilla) hizo esta [introducción futurística a Mastodon](https://wordsmith.social/elilla/a-futuristic-mastodon-introduction-for-2021).

Si aún estás confundido, preguntame: https://social.pueseso.club/@diazepan

## ¿Cómo puedo contribuir a la guía?

Mirá [la guía de contribuciones](contributing.md)!
