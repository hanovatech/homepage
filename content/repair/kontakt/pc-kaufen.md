---
title: PC-Kaufberatung Formular
---

# PC-Kaufberatung Formular

**Sie benötigen Hilfe bei der Wahl eines neuen PCs?** Dann nehmen Sie mit uns über das folgende Formular Kontakt auf.

Wir werden uns schnellstmöglich bei Ihnen melden, um mit Ihnen einen Termin zu vereinbaren. Alternativ können Sie uns auch telefonisch unter [0511-51561190](tel:051151561190) zu unseren Öffnungszeiten erreichen.

<div class="not-prose max-w-2xl mx-auto mt-16 bg-gray-50 p-3 sm:p-6 border rounded-lg shadow-lg">
  <form name="repair-pc-kaufen" method="POST" action="/repair/kontakt/success/" netlify>
    <input type="hidden" name="subject" id="subject" value="get dynamically set by js" />
    <div class="grid grid-cols-1 gap-y-6 gap-x-8 sm:grid-cols-2">
      <h2 class="sm:col-span-2 text-2xl text-gray-900 font-bold mb-0">Angaben zur Verwendung</h2>
      <div class="sm:col-span-2">
        <label for="usecases" class="block text-sm font-semibold leading-6 text-gray-900">Nutzungsbereich</label>
        <div class="mt-2.5">
          <select name="usecases" id="usecases" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="bitte-auswaehlen" selected="selected">Bitte auswählen </option>
            <option value="privat-office-office-internet-and-leichte-apps-or-ab-400eur">Privat-Office (Office, Internet &amp; leichte Apps) | ab 400€</option>
            <option value="gaming-leistungsintensive-spiele-or-ab-800eur">Gaming (Leistungsintensive Spiele) | ab 800€</option>
            <option value="business-basics-office-internet-and-leichte-apps-or-ab-700eur">Business-Basics (Office, Internet &amp; leichte Apps) | ab 700€</option>
            <option value="business-premium-leistungsintensive-programme-or-ab-1000eur">Business-Premium (Leistungsintensive Programme) | ab 1000€</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="manufacturer" class="block text-sm font-semibold leading-6 text-gray-900">Bevorzugter Hersteller</label>
        <div class="mt-2.5">
          <select name="manufacturer" id="manufacturer" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="beliebig">Beliebig</option>
            <option value="acer">Acer</option>
            <option value="alienware">Alienware</option>
            <option value="apple">Apple</option>
            <option value="asus">Asus</option>
            <option value="csl">CSL</option>
            <option value="dell">Dell</option>
            <option value="fujitsu">Fujitsu</option>
            <option value="hanovatech-massgeschneiderter-computer" selected="selected">HanovaTech (Maßgeschneiderter Computer)</option>
            <option value="hp">HP</option>
            <option value="lenovo">Lenovo</option>
            <option value="msi">MSI</option>
            <option value="toshiba">Toshiba</option>
            <option value="wortmann-ag-terra">Wortmann AG (Terra)</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="os" class="block text-sm font-semibold leading-6 text-gray-900">Betriebssystem</label>
        <div class="mt-2.5">
          <select name="os" id="os" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="windows" selected="selected">Windows</option>
            <option value="linux">Linux</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-1">
        <label for="cpu-manufacturer" class="block text-sm font-semibold leading-6 text-gray-900">CPU-Hersteller</label>
        <div class="mt-2.5">
          <select name="cpu-manufacturer" id="cpu-manufacturer" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="beliebig" selected="selected">Beliebig</option>
            <option value="intel">Intel</option>
            <option value="amd">AMD</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-1">
        <label for="ram" class="block text-sm font-semibold leading-6 text-gray-900">Arbeitsspeicher (RAM)</label>
        <div class="mt-2.5">
          <select name="ram" id="ram" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="beliebig" selected="selected">Beliebig</option>
            <option value="8gb-office-pc">8GB (Office-PC)</option>
            <option value="16gb-hochleistung-pc">16GB (Hochleistung-PC)</option>
            <option value="32gb-hochleistung-pc">32GB (Hochleistung-PC)</option>
            <option value="64gb-sehr-hohe-leistung">64GB (Sehr hohe Leistung)</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-1">
        <label for="disk-1" class="block text-sm font-semibold leading-6 text-gray-900">1. Festplatte (SSD)</label>
        <div class="mt-2.5">
          <select name="disk-1" id="disk-1" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="512gb-office-pc" selected="selected">512GB (Office-PC)</option>
            <option value="1tb-hohe-kapazitaet-ist-wichtig">1TB (hohe Kapazität ist wichtig)</option>
            <option value="2tb-sehr-hohe-kapazitaet-ist-wichtig">2TB (sehr hohe Kapazität ist wichtig)</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-1">
        <label for="disk-2" class="block text-sm font-semibold leading-6 text-gray-900">2. Festplatte (HDD)</label>
        <div class="mt-2.5">
          <select name="disk-2" id="disk-2" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="nicht-relevant">nicht relevant</option>
            <option value="1tb" selected="selected">1TB </option>
            <option value="2tb">2TB </option>
            <option value="4tb">4TB</option>
            <option value="8tb">8TB</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="software" class="block text-sm font-semibold leading-6 text-gray-900">Welche Software oder Spiele sollen auf dem Rechner laufen?</label>
        <div class="mt-2.5">
          <input type="text" name="software" id="software" placeholder="z.B. Photoshop oder Call of Duty Warzone" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="service" class="block text-sm font-semibold leading-6 text-gray-900">Das Angebot muss folgende Dienstleistungen beinhalten</label>
        <div class="mt-2.5">
          <select name="service" id="service" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="keine">Keine</option>
            <option value="pc-einrichtung-windows-and-treiber-installation" selected="selected">PC-Einrichtung (Windows &amp; Treiber Installation)</option>
            <option value="datenuebertragung">Datenübertragung</option>
            <option value="pc-einrichtung-software-installation">PC-Einrichtung + Software Installation</option>
            <option value="pc-einrichtung-datenuebertragung">PC-Einrichtung + Datenübertragung </option>
            <option value="plug-and-play-beinhalte-alle-o-g-dienstleistungen">Plug &amp; Play (beinhalte alle o. g. Dienstleistungen)</option>
          </select>
        </div>
      </div>
      <h2 class="sm:col-span-2 text-2xl text-gray-900 font-bold mb-0 mt-6">Ihre Kontaktdaten</h2>
      <div>
        <label for="firstname" class="block text-sm font-semibold leading-6 text-gray-900">Vorname</label>
        <div class="mt-2.5">
          <input type="text" name="firstname" id="firstname" required autocomplete="given-name" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div>
        <label for="lastname" class="block text-sm font-semibold leading-6 text-gray-900">Nachname</label>
        <div class="mt-2.5">
          <input type="text" name="lastname" id="lastname" required autocomplete="family-name" oninput="this.form.elements[1].value = 'Kaufberatung - ' + this.value" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="company" class="block text-sm font-semibold leading-6 text-gray-900">Unternehmen</label>
        <div class="mt-2.5">
          <input type="text" name="company" id="company" autocomplete="organization" oninput="this.form.elements[1].value = 'Kaufberatung - ' + this.value" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
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
          <input type="text" name="address" id="address" autocomplete="tel" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600" placeholder="Musterstraße 1, 12345 Musterort">
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