<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0c0f,60:0e7490,100:22d3ee&height=170&section=header&text=Fernando%20González%20Berlanga&fontColor=ffffff&fontSize=38&fontAlignY=36&desc=Construyo%20software%20que%20negocios%20reales%20usan%20para%20operar&descSize=15&descAlignY=58" width="100%" alt="Fernando González Berlanga" />

<p align="center">
  Estudiante de ingeniería en el <b>Tec de Monterrey</b>, campus Saltillo.<br />
  Fundador de <a href="https://zyria.site"><b>Zyria</b></a>, donde diseño y programo el software que usan mis clientes todos los días.
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,supabase,postgres,python,vercel" alt="Stack" />
</p>

<p align="center">
  <sub>La mayor parte de mi código vive en repos privados porque es trabajo de clientes.<br />
  Abajo está todo, con enlace a lo que se puede ver funcionando.</sub>
</p>

---

## Lo que estoy construyendo

<table>
<tr>
<td width="50%" valign="top">

### Zyria

<a href="https://zyria.site"><img src="https://raw.githubusercontent.com/ferzglzb/ferzglzb/main/img/zyria.png" alt="Zyria" /></a>

Marca paraguas de tres productos de software para negocios locales. Yo hago el producto, el diseño y la infraestructura.

**Next.js · Supabase con RLS · Vercel**

[zyria.site](https://zyria.site)

</td>
<td width="50%" valign="top">

### Antojo

<p align="center"><a href="https://antojo.zyria.site"><img src="https://raw.githubusercontent.com/ferzglzb/ferzglzb/main/img/antojo.png" alt="Antojo" height="320" /></a></p>

Menús digitales para restaurantes. **7 menús en vivo**, y cada marca lleva su propio sistema de diseño en vez de una plantilla recoloreada.

Mobile first: el 95% de los comensales lo abre desde el celular.

[antojo.zyria.site](https://antojo.zyria.site)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Velada

<a href="https://zyria.site/invitaciones/"><img src="https://raw.githubusercontent.com/ferzglzb/ferzglzb/main/img/velada.png" alt="Velada" /></a>

Invitaciones digitales que se abren como una mini película: música compuesta a la medida, animaciones al tema y confirmación por WhatsApp, así la lista de invitados se arma sola.

**14 demos en vivo**, cada una con su propio sistema de diseño.

[zyria.site/invitaciones](https://zyria.site/invitaciones/)

</td>
<td width="50%" valign="top">

### Bloque

<p align="center"><a href="https://bloque.zyria.site"><img src="https://raw.githubusercontent.com/ferzglzb/ferzglzb/main/img/bloque.png" alt="Bloque" height="320" /></a></p>

Mi app de estudiante: horario, materias y pendientes en un lugar, con widget de pantalla de inicio para iOS que dice cuánto falta para la siguiente clase.

La uso todos los días.

[bloque.zyria.site](https://bloque.zyria.site)

</td>
</tr>
</table>

---

## Código público

### [sapal-stl](https://github.com/ferzglzb/sapal-stl)

Generador paramétrico de ruedas impresas en 3D, con `numpy` y nada más.

Escribir triángulos a un STL es fácil. Que la malla quede **cerrada** es lo difícil: cada arista tiene que pertenecer a exactamente dos triángulos y todas las normales tienen que apuntar hacia afuera. Mis primeras versiones salían con 960 aristas sin pareja.

En vez de corregir cada superficie a mano, escribí un corrector que une vértices, propaga el devanado por inundación BFS y decide la orientación global con el volumen con signo. Ahora puedes escribir la geometría como se te ocurra y sale bien de todos modos.

Nació porque el laboratorio de impresión de la escuela rechaza mallas rotas y no las arregla por ti.

`3d-printing` · `computational-geometry` · `mesh-processing` · `numpy`

---

## Demos

Propuestas que armé completas para enseñar de qué se trata, sin que el cliente tuviera que imaginárselo. Es como vendo: mando la cosa funcionando en vez de prometerla.

**[ANKA Soluciones Industriales](https://anka-web-mu.vercel.app)** · Sitio para un fabricante de racks y contenedores metálicos. El hero recorre cuadro por cuadro un render 3D conforme bajas. Dirección industrial, tipografía condensada.

---

## En producción con clientes

| Proyecto | Qué hace | Estado |
|---|---|---|
| **Casa Canina** | Sistema de gestión para guardería y hotel canino. Agente de WhatsApp que confirma, recuerda y avisa. **800+ clientes registrados, 15 a 30 servicios al día.** | En producción, cliente activo |
| **Nexo** | CRM multi-tenant: agenda, reserva pública, comisiones, inventario y roles. Más un agente de voz que contesta el teléfono y agenda solo. **Construido de cero a producción en 3 días.** | En producción |
| **Velada** | Invitaciones digitales. **14 demos en vivo** y un asistente de pedido con vista previa que se dibuja mientras el cliente elige. | Vendiendo, con pedidos pagados |
| **La Cipolla** | Menú digital de trattoria: 61 platillos en español e inglés, con asistente de IA. | Entregado |

---

<p align="center">
  <a href="https://zyria.site"><b>zyria.site</b></a>
</p>
