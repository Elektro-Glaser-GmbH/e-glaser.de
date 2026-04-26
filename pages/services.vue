<script setup lang="ts">
useSeoMeta({
  title: 'Dienstleistungen – Elektro-Glaser',
  description: 'Innovative Lösungen für Ihre Elektrobedürfnisse – von Stecker-Solar bis Wallbox, von Smart Home bis PV-Anlage.',
  ogTitle: 'Dienstleistungen – Elektro-Glaser',
  ogDescription: 'Innovative Lösungen für Ihre Elektrobedürfnisse – von Stecker-Solar bis Wallbox, von Smart Home bis PV-Anlage.',
})
</script>

<template>
  <div class="section container">
    <p class="section-label">Dienstleistungen</p>
    <h1>Innovative Lösungen für Ihre Elektrobedürfnisse</h1>
    <hr />

    <h2>Elektriker im Paket – einfach &amp; unkompliziert</h2>
    <p>
      Warum müssen Dienstleistungen im Handwerk immer so kompliziert sein? Anrufen, erklären, Termin machen, Angebot
      einholen, annehmen, nochmal Termine... Geht es nicht auch einfach? Hier finden Sie eine Auswahl kleiner
      Elektriker-Pakete, die Sie schnell und unkompliziert anfragen können.
    </p>

    <div class="service-grid">
      <div class="service-card">
        <div class="service-icon">🔆</div>
        <h3>Stecker-Solar-Check</h3>
        <p>Wir prüfen in wenigen Minuten, ob und wie eine Stecker-Solaranlage (Balkonkraftwerk) bei Ihnen möglich ist.</p>
        <p><strong>Leistung:</strong> Vor-Ort-Check, Beratung, Empfehlung geeigneter Geräte</p>
      </div>
      <div class="service-card">
        <div class="service-icon">🚗</div>
        <h3>Wallbox-Check &amp; Installation</h3>
        <p>Wir prüfen Ihren Hausanschluss, empfehlen die passende Wallbox und übernehmen die Installation – inklusive Anmeldung beim Netzbetreiber.</p>
        <p><strong>Leistung:</strong> Hausanschluss-Check, Wallbox-Montage, Netzanmeldung</p>
      </div>
      <div class="service-card">
        <div class="service-icon">🌞</div>
        <h3>PV-Anlage &amp; Speicher</h3>
        <p>Von der kleinen Dachanlage bis zur großen PV-Installation mit Batteriespeicher. Wir begleiten Sie von der Planung bis zur Inbetriebnahme.</p>
        <p><strong>Leistung:</strong> Planung, Anlagenauslegung, Montage, Netzanmeldung, Förderberatung</p>
      </div>
      <div class="service-card">
        <div class="service-icon">🏠</div>
        <h3>Smart Home &amp; Automatisierung</h3>
        <p>Lichtsteuerung, smarte Steckdosen, Energiemonitoring – wir zeigen Ihnen, was wirklich sinnvoll ist.</p>
        <p><strong>Leistung:</strong> Beratung, Installation, Konfiguration</p>
      </div>
      <div class="service-card">
        <div class="service-icon">🔌</div>
        <h3>Elektroinstallation</h3>
        <p>Steckdosen, Leitungsverlegung, Sicherungskasten, Unterverteilung – alle klassischen Elektroarbeiten, schnell und sauber ausgeführt.</p>
        <p><strong>Leistung:</strong> Neu- und Erweiterungsinstallation, Prüfung bestehender Anlagen</p>
      </div>
      <div class="service-card">
        <div class="service-icon">♻️</div>
        <h3>Wärmepumpen-Anschluss</h3>
        <p>Elektrischer Anschluss von Wärmepumpen, Prüfung des Hausanschlusses auf Eignung, Abstimmung mit Netzbetreiber nach § 14a EnWG.</p>
        <p><strong>Leistung:</strong> Anschluss, Anmeldung, Abstimmung Netzbetreiber</p>
      </div>
    </div>

    <hr />
    <h2>Unsere Schwerpunkte im Detail</h2>

    <div class="feature-row">
      <div class="feature-img">
        <img src="/img/smart-home.jpg" alt="Photovoltaik und erneuerbare Energien" />
      </div>
      <div class="feature-text">
        <h3>Erneuerbare Energien</h3>
        <p>Von der kleinen Stecker-Solar-Anlage bis zur großen Dach-PV mit Batteriespeicher – wir kennen alle Förderprogramme und begleiten Sie durch den gesamten Prozess: Planung, Anmeldung, Montage, Inbetriebnahme.</p>
      </div>
    </div>

    <div class="feature-row reverse">
      <div class="feature-img">
        <img src="/img/solar-roof.jpg" alt="Wallbox und E-Mobilität" />
      </div>
      <div class="feature-text">
        <h3>Elektromobilität &amp; Wallbox</h3>
        <p>Wir prüfen Ihren Hausanschluss, empfehlen die passende Ladestation und übernehmen Montage sowie Anmeldung beim Netzbetreiber. Auf Wunsch mit Lastmanagement und PV-Überschussladen.</p>
      </div>
    </div>

    <div class="feature-row">
      <div class="feature-img">
        <img src="/img/electrician.jpg" alt="Sicherungskasten und Elektroinstallation" />
      </div>
      <div class="feature-text">
        <h3>Elektroinstallation</h3>
        <p>Ob einzelne Steckdose, neue Unterverteilung oder komplette Neuinstallation – wir erledigen klassische Elektroarbeiten schnell und sauber. Auch für Arbeiten, für die andere Elektriker zu selten Zeit haben.</p>
      </div>
    </div>
  </div>
</template>
