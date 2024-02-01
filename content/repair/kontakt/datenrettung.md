---
title: Datenrettung Formular
---

# Datenrettung Formular

**Sie haben wichtige Daten verloren?** Dann nehmen Sie mit uns über das folgende Formular Kontakt auf.

Wir werden uns schnellstmöglich bei Ihnen melden, um mit Ihnen einen Termin zu vereinbaren. Alternativ können Sie uns auch telefonisch unter [0511-51561190](tel:051151561190) zu unseren Öffnungszeiten erreichen.

Art des Datenträgers Select
Menge an Daten Text
Beschreibung Textarea

<div class="not-prose max-w-2xl mx-auto mt-16 bg-gray-50 p-3 sm:p-6 border rounded-lg shadow-lg">
  <form name="repair-datenrettung" method="POST" action="/repair/kontakt/success/" netlify>
    <input type="hidden" name="subject" value="Datenrettung - %{submissionId}" />
    <div class="grid grid-cols-1 gap-y-6 gap-x-8 sm:grid-cols-2">
      <h2 class="sm:col-span-2 text-2xl text-gray-900 font-bold mb-0">Angaben zum Problem</h2>
      <div class="sm:col-span-2">
        <label for="disktype" class="block text-sm font-semibold leading-6 text-gray-900">Art des Datenträgers</label>
        <div class="mt-2.5">
          <select name="disktype" id="disktype" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="" class="placeholder" disabled="" selected="selected">Bitte auswählen</option>
            <option value="Interne Festplatte">Interne Festplatte</option>
            <option value="Externe Festplatte">Externe Festplatte</option>
            <option value="USB Stick">USB Stick</option>
            <option value="Smartphone">Smartphone</option>
            <option value="SD Karte">SD Karte</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="amount" class="block text-sm font-semibold leading-6 text-gray-900">Wie groß ist ca. die Datenmenge? (in GB)</label>
        <div class="mt-2.5">
          <input type="text" name="amount" id="amount" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="message" class="block text-sm font-semibold leading-6 text-gray-900">Wie kam es zum Datenverlust?</label>
        <div class="mt-2.5">
          <textarea name="message" id="message" rows="4" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600"></textarea>
        </div>
      </div>
      <h2 class="sm:col-span-2 text-2xl text-gray-900 font-bold mb-0">Ihre Kontaktdaten</h2>
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