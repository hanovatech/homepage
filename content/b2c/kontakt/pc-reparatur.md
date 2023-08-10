---
title: PC-Reparatur Formular
---

# PC-Reparatur Formular

**Sie haben Probleme mit Ihrem PC?** Dann nehmen Sie mit uns über das folgende Formular Kontakt auf.

Wir werden uns schnellstmöglich bei Ihnen melden, um mit Ihnen einen Termin zu vereinbaren. Alternativ können Sie uns auch telefonisch unter [0511-51561190](tel:051151561190) zu unseren Öffnungszeiten erreichen.

<div class="not-prose max-w-2xl mx-auto mt-16 sm:bg-gray-50 sm:p-6 sm:border sm:rounded-lg sm:shadow-lg">
  <form name="datenrettung" data-netlify="true" method="POST" action="/b2c/kontakt/success">
    <div class="grid grid-cols-1 gap-y-6 gap-x-8 sm:grid-cols-2">
      <h2 class="sm:col-span-2 text-2xl text-gray-900 font-bold mb-0">Angaben zum Problem</h2>
      <div class="sm:col-span-2">
        <label for="kind" class="block text-sm font-semibold leading-6 text-gray-900">Art des PCs</label>
        <div class="mt-2.5">
          <select name="kind" id="kind" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="bitte-auswaehlen" selected="selected">Bitte auswählen...</option>
            <option value="selbstgebaut">Selbstgebaut</option>
            <option value="zusammengebaut-durch-drittanbieter-z-b-csl">Zusammengebaut (durch Drittanbieter z. B. CSL) </option>
            <option value="markengeraet-z-b-acer">Markengerät z. B. Acer</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="problem" class="block text-sm font-semibold leading-6 text-gray-900">Welches Problem hat Ihr Notebook?</label>
        <div class="mt-2.5">
          <select name="problem" id="problem" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="bitte-auswaehlen" selected="selected">Bitte auswählen</option>
            <option value="pc-startet-nicht">PC Startet nicht</option>
            <option value="windows-faehrt-nicht-hoch">Windows fährt nicht hoch</option>
            <option value="blue-screen-windows-stuerzt-ab">Blue Screen/ Windows stürzt ab</option>
            <option value="geraet-faehrt-hoch-aber-ohne-bildsignal-black-screen">Gerät fährt hoch, aber ohne Bildsignal (black Screen)</option>
            <option value="an-aus-schleife">AN/AUS Schleife</option>
            <option value="keine-internetverbindung">Keine Internetverbindung</option>
            <option value="computer-ist-zu-langsam">Computer ist zu langsam</option>
            <option value="hardware-muss-ausgetauscht-werden">Hardware muss ausgetauscht werden</option>
            <option value="sonstiges">Sonstiges</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="cause" class="block text-sm font-semibold leading-6 text-gray-900">Was ist die Ursache des Problems?</label>
        <div class="mt-2.5">
          <select name="cause" id="cause" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="was-ist-passiert" selected="selected">Was ist passiert?</option>
            <option value="nicht-bekannt">Nicht bekannt</option>
            <option value="ueberspannung">Überspannung</option>
            <option value="geraet-ist-waehrend-spielen-arbeiten-abgestuerzt">Gerät ist während Spielen/ Arbeiten abgestürzt</option>
            <option value="bios-upgrade">Bios Upgrade</option>
            <option value="hardwaretausch">Hardwaretausch</option>
            <option value="schadsoftware">Schadsoftware</option>
            <option value="sonstiges">Sonstiges</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="message" class="block text-sm font-semibold leading-6 text-gray-900">Erklärung zum Problem</label>
        <div class="mt-2.5">
          <textarea name="message" id="message" required rows="4" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600"></textarea>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="repaircost" class="block text-sm font-semibold leading-6 text-gray-900">Reparaturkosten</label>
        <div class="mt-2.5">
          <select name="repaircost" id="repaircost" required class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="reparaturkosten-freigabe-auswaehlen" selected="selected">Reparaturkosten Freigabe auswählen</option>
            <option value="reparatur-ausfuehren-bis-100eur">Reparatur ausführen bis 100€</option>
            <option value="reparatur-ausfuehren-bis-200eur">Reparatur ausführen bis 200€</option>
            <option value="reparatur-ausfuehren-bis-300eur">Reparatur ausführen bis 300€</option>
            <option value="reparatur-ausfuehren-bis-400eur">Reparatur ausführen bis 400€</option>
            <option value="reparatur-ausfuehren-bis-500eur">Reparatur ausführen bis 500€</option>
            <option value="reparatur-ausfuehren-bis-1000eur">Reparatur ausführen bis 1000€</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="data-saving" class="block text-sm font-semibold leading-6 text-gray-900">Sollen wir eine Datensicherung mit anbieten?</label>
        <fieldset class="mt-4">
          <legend class="sr-only">Datensicherung notwendig?</legend>
          <div class="space-y-4">
            <div class="flex items-center">
              <input id="data-saving-yes" name="notification-method" type="radio" checked class="h-4 w-4 border-gray-300 text-blue-600 focus:ring-blue-600">
              <label for="data-saving-yes" class="ml-3 block text-sm font-light leading-6 text-gray-900">Ja, die Daten müssen vor der Reparatur gerettet bzw. gesichert werden</label>
            </div>
            <div class="flex items-center">
              <input id="data-saving-no" name="notification-method" type="radio" class="h-4 w-4 border-gray-300 text-blue-600 focus:ring-blue-600">
              <label for="data-saving-no" class="ml-3 block text-sm font-light leading-6 text-gray-900">Nein, ich habe meine Daten schon gesichert</label>
            </div>
            <div class="flex items-center">
              <input id="data-saving-delete" name="notification-method" type="radio" class="h-4 w-4 border-gray-300 text-blue-600 focus:ring-blue-600">
              <label for="data-saving-delete" class="ml-3 block text-sm font-light leading-6 text-gray-900">Alle Daten auf dem Gerät können gelöscht werden</label>
            </div>
          </div>
        </fieldset>
      </div>
      <div class="sm:col-span-2">
        <label for="pickup" class="block text-sm font-semibold leading-6 text-gray-900">Sollen wir das Gerät abholen?</label>
        <div class="mt-2.5">
          <select name="pickup" id="pickup" required class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="nein-geraet-wird-vor-ort-abgegeben-buero" selected="selected">Nein, Gerät wird vor Ort abgegeben (Büro)</option>
	          <option value="ja-fuer-29-99eur-innerhalb-hannover">Ja (für 29,99€ innerhalb Hannover)</option>
          </select>
        </div>
      </div>
      <h2 class="sm:col-span-2 text-2xl text-gray-900 font-bold mb-0 mt-6">Ihre Kontaktdaten</h2>
      <div>
        <label for="firstname" class="block text-sm font-semibold leading-6 text-gray-900">Vorname</label>
        <div class="mt-2.5">
          <input type="text" name="first-name" id="first-name" required autocomplete="given-name" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div>
        <label for="lastname" class="block text-sm font-semibold leading-6 text-gray-900">Nachname</label>
        <div class="mt-2.5">
          <input type="text" name="last-name" id="last-name" required autocomplete="family-name" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="company" class="block text-sm font-semibold leading-6 text-gray-900">Unternehmen</label>
        <div class="mt-2.5">
          <input type="text" name="company" id="company" autocomplete="organization" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="email" class="block text-sm font-semibold leading-6 text-gray-900">Email</label>
        <div class="mt-2.5">
          <input type="email" name="email" id="email" required autocomplete="email" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="phone-number" class="block text-sm font-semibold leading-6 text-gray-900">Telefon</label>
        <div class="relative mt-2.5">
          <input type="tel" name="phone-number" id="phone-number" autocomplete="tel" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="address" class="block text-sm font-semibold leading-6 text-gray-900">Adresse</label>
        <div class="relative mt-2.5">
          <input type="tel" name="address" id="address" autocomplete="tel" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600" placeholder="Musterstraße 1, 12345 Musterort">
        </div>
      </div>
      <div class="flex gap-x-4 sm:col-span-2">
        <div class="flex h-6 items-center">
          <input type="checkbox" name="privacy" class="rounded-md" required />
        </div>
        <label class="text-sm leading-6 text-gray-600" id="switch-1-label">
          Ich akzeptiere die 
          <a href="/datenschutz" class="font-semibold text-blue-600">Datenschutzerklärung</a>
        </label>
      </div>
    </div>
    <div class="mt-10">
      <button type="submit" class="block w-full rounded-md bg-blue-600 px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600 duration-200">
        Anfrage abschicken
      </button>
    </div>
  </form>
</div>