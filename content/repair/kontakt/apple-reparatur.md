---
title: Apple-Reparatur Formular
---

# Apple-Reparatur Formular

**Sie haben Probleme mit Ihrem MacBook oder iPad?** Dann nehmen Sie mit uns über das folgende Formular Kontakt auf.

Wir werden uns schnellstmöglich bei Ihnen melden, um mit Ihnen einen Termin zu vereinbaren. Alternativ können Sie uns auch telefonisch unter [0511-51512490](tel:051151512490) zu unseren Öffnungszeiten erreichen.

<div class="not-prose max-w-2xl mx-auto mt-16 bg-gray-50 p-3 sm:p-6 border rounded-lg shadow-lg">
  <form name="repair-laptop-reparatur" method="POST" action="/repair/kontakt/success/" netlify>
    <div class="grid grid-cols-1 gap-y-6 gap-x-8 sm:grid-cols-2">
      <h2 class="sm:col-span-2 text-2xl text-gray-900 font-bold mb-0">Angaben zum Problem</h2>
      <div class="sm:col-span-2">
        <label for="problem" class="block text-sm font-semibold leading-6 text-gray-900">Welches Problem hat Ihr Apple-Gerät?</label>
        <div class="mt-2.5">
          <select name="problem" id="problem" required="required" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="" class="placeholder" disabled="" selected="selected">Bitte auswählen</option>
            <option value="Gerät Startet nicht">Gerät Startet nicht</option>
            <option value="Das Gerät befindet sich in einer Endlosschleife beim Hochfahren">Das Gerät befindet sich in einer Endlosschleife beim Hochfahren</option>
            <option value="Gerät fährt hoch, aber ohne Bildsignal ">Gerät fährt hoch, aber ohne Bildsignal</option>
            <option value="Das Gerät bleibt beim Start bei Apple-Logo hängen">Das Gerät bleibt beim Start bei Apple-Logo hängen</option>
            <option value="Das Gerät schaltet sich während des Betriebs automatisch aus">Das Gerät schaltet sich während des Betriebs automatisch aus</option>
            <option value="Das Update bricht kontinuierlich ab">Das Update bricht kontinuierlich ab</option>
            <option value="Gerät ist sehr langsam">Gerät ist sehr langsam</option>
            <option value="Verdacht auf einen Trojaner oder einen Hackerangriff">Verdacht auf einen Trojaner oder einen Hackerangriff</option>
            <option value="Bildschirm ist beschädigt">Bildschirm ist beschädigt</option>
            <option value="Tastatur-Problem">Tastatur-Problem</option>
            <option value="Gehäuse ist beschädigt ">Gehäuse ist beschädigt </option>
            <option value="Akku lädt nicht mehr">Akku lädt nicht mehr</option>
            <option value="Akkuleistung ist zu niedrig">Akkuleistung ist zu niedrig</option>
            <option value="TouchPad funktioniert nicht">TouchPad funktioniert nicht</option>
            <option value="TouchBar funktioniert nicht">TouchBar funktioniert nicht</option>
            <option value="Datenverlust">Datenverlust</option>
            <option value="Sonstiges">Sonstiges</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="cause" class="block text-sm font-semibold leading-6 text-gray-900">Was ist die mögliche Ursache des Problems?</label>
        <div class="mt-2.5">
          <select name="cause" id="cause" required class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="" class="placeholder" disabled="" selected="selected">Was ist passiert?</option>
            <option value="Keine Vorkommnisse ">Keine Vorkommnisse</option>
            <option value="Gerät ist runtergefallen">Gerät ist runtergefallen</option>
            <option value="Wasserschäden (Flüssigkeit ohne Zucker)">Wasserschäden (Flüssigkeit ohne Zucker)</option>
            <option value="Flüssigkeitsschäden (Flüssigkeit mit Zucker)">Flüssigkeitsschäden (Flüssigkeit mit Zucker)</option>
            <option value="Überspannung">Überspannung</option>
            <option value="Updates">Updates</option>
            <option value="Sonstiges">Sonstiges</option>
          </select>
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="message" class="block text-sm font-semibold leading-6 text-gray-900">Erklärung zum Problem</label>
        <div class="mt-2.5">
          <textarea name="message" id="message" rows="4" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600"></textarea>
        </div>
      </div>
      <div>
        <label for="product" class="block text-sm font-semibold leading-6 text-gray-900">Produkt</label>
        <div class="mt-2.5">
          <select name="product" id="product" required class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
            <option value="" class="placeholder" disabled="" selected="selected">Bitte auswählen</option>
            <option value="MacBook">MacBook</option>
            <option value="iMac">iMac</option>
            <option value="Mac mini">Mac mini</option>
            <option value="iPad">iPad</option>
            <option value="iPhone">iPhone</option>
          </select>
        </div>
      </div>
      <div>
        <label for="modell" class="block text-sm font-semibold leading-6 text-gray-900">Modell/Jahr</label>
        <div class="mt-2.5">
          <input type="text" name="modell" id="modell" placeholder="z.B. Pro 2019 16 Zoll" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
        </div>
      </div>
      <div class="sm:col-span-2">
        <label for="serialnumber" class="block text-sm font-semibold leading-6 text-gray-900">Seriennummer</label>
        <div class="mt-2.5">
          <input type="text" name="serialnumber" id="serialnumber" class="block w-full rounded-md border-0 py-2 px-3.5 text-sm leading-6 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-blue-600">
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