---
title: Principios de la WCAG
date: '2022-05-07'
tags: ['Accesibilidad', 'WCAG']
draft: false
summary: Aunque las WCAG no son perfectas, es muy importante conocer y tener presente sus 4 principios para poder evaluar la accesibilidad en nuestros desarrollos.
---

La accesibilidad web es un tema por el que tengo especial interés. A mi juicio, toda persona debe tener acceso a los recursos web que tanto nos ayudan a crecer personal y profesionalmente (así como también nos entretienen 😉).

Sin embargo, conviene subrayar qué es la accesibilidad y qué c#%”8!😤 significa esto de la WCAG, antes de comenzar con sus principios.

La **accesibilidad** web no es más que un concepto de desarrollo que busca **asegurar una buena experiencia de usuario para las personas con capacidades reducidas**.

_Ok... todo bien hasta ahí pero ¿qué es WCAG?!!..._ 😬

WCAG (Web Content Accessibility Guidelines, en español **Pautas de Accesibilidad para el Contenido Web**), son recomendaciones creadas por la W3C (World Wide Web Consortium) con el objetivo de crear un estándar para que el contenido web sea más accesible.

_Cito de su página:_

> Los documentos WCAG explican cómo hacer el contenido web más accesible para las personas con discapacidad. Por “contenido” web se hace referencia, generalmente, a la información que se puede encontrar en una página o aplicación web, lo cual incluye: Información natural como textos, imágenes y sonidos; Código o marcado que define la estructura, la presentación, etc.

Dentro de las WCAG tenemos 12 criterios, que a su vez se divide cada uno en 3 niveles que determinan el nivel de inversión que se hará en accesibilidad. Nivel A (básico), Nivel AA (Intermedio) y Nivel AAA (Más alto). _Esto último lo dejaré para otro artículo._

_Ahora se viene lo bueno…_ 🤓

## Principios de WCAG

Las WCAG no son perfectas, pero es muy importante tener presente sus 4 principios para que nuestras páginas web sean más accesibles. _Trate de ser lo más llana posible en la descripción de los mismos_:

1. **Perceptible: Todo lo que presentes en la web debe ser percibido por tus usuarios** _(que les llegue al cerebro y lo interpreten)_.

   Por ejemplo, quieres mostrar una información a tus usuarios pero solo tienes una manera de mostrar esa información, dígase visualmente por la interfaz gráfica pero tus usuarios no tienen acceso a la pantalla o no tiene la visión, como resultado esos usuarios no podrán recibir esa información. Entonces lo ideal sería apoyarse también de un formato más accesible como lo es el texto. El texto suele ser uno de los elementos más perceptibles ya que puede ser leído por el usuario o por un lector de pantalla, traducido, ampliado, etc.

2. **Operable: Tu web no debe depender de un ratón o de un teclado** para que cualquier usuario que por cualquier motivo no disponga de estos dispositivos pueda tener alternativas para operar tu sitio.

   Cuando desarrollamos una web operable, le quitamos la dependencia del ratón y teclado para recibir a todos esos usuarios que navegan por la web de una manera diferente.

3. **Comprensible: Cualquier persona que use tu página debe poder entenderla**, debe comprender qué les estás diciendo. ¿Qué hace tu sitio?, ¿Cómo operarlo?, ¿Qué información requiere tu sitio de tus usuarios?, ¿Cómo suministrar esa información?

   Por ejemplo al llenar un formulario o si están realizando otro paso, que sepan si cometieron un error y que sepan cómo corregirlo.

4. **Robusto: Debe ser operable sin importar en contexto desde donde es utilizado**.

   Por ejemplo: Si, algunos usuarios usarán el Internet Explorer, crea tu sitio para que sea compatible tanto con los últimos navegadores como con los más viejitos. Igualmente piensa en el hardware, no todos tus usuarios tendrán dispositivos modernos. Otro punto importante es que pienses en la conectividad, la banda ancha no llega a todos lados y hay lugares donde la conectividad es muy precaria.

**Si tenemos en cuenta estos cuatro principios al momento de desarrollar estaríamos aplicando la lógica para saber si nuestros sitios web son realmente accesibles.**

Fuente: [Introducción a las Pautas de Accesibilidad para el Contenido Web (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/es)
