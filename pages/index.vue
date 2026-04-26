<script setup lang="ts">
useSeoMeta({
  title: 'Elektro-Glaser – Ihr Elektriker in Erlangen',
  description: 'Erneuerbare Energien, Smart Home & Elektromobilität – inhabergeführt, kompetent, aus Erlangen.',
  ogTitle: 'Elektro-Glaser – Ihr Elektriker in Erlangen',
  ogDescription: 'Erneuerbare Energien, Smart Home & Elektromobilität – inhabergeführt, kompetent, aus Erlangen.',
})
</script>

<template>
  <div>
    <!-- Hero -->
    <section class="hero">
      <div class="container">
        <span class="section-label">Ihr Partner in Erlangen &amp; Umgebung</span>
        <h1>Strom mit <span class="accent">Verstand.</span></h1>
        <p class="hero-sub">Erneuerbare Energien · Smart Home · Elektromobilität</p>
        <p class="lead">
          Wir sind ein inhabergeführter Elektrobetrieb aus Erlangen – mit Leidenschaft für zukunftsfähige Technik,
          klare Kommunikation und nachhaltige Lösungen. Vom Balkonsolar bis zur großen PV-Anlage, von der Wallbox bis
          zum Smart Home.
        </p>
        <NuxtLink to="/contact" class="btn-hero">Jetzt Angebot anfragen</NuxtLink>
      </div>
    </section>

    <!-- Kernleistungen -->
    <section class="section container">
      <h2 class="text-center">Unsere Kernleistungen</h2>
      <p class="section-label text-center">Was wir für Sie tun</p>
      <div class="service-grid">
        <div class="service-card">
          <div class="service-icon">🌞</div>
          <h3>Photovoltaik &amp; Balkonsolar</h3>
          <p>Von der kleinen Stecker-Solar-Anlage bis zur Dach-PV – wir prüfen, beraten und installieren. Eigenverbrauchsoptimierung inklusive.</p>
        </div>
        <div class="service-card">
          <div class="service-icon">🚗</div>
          <h3>Wallbox &amp; E-Mobilität</h3>
          <p>Ladepunkt zuhause, Lastmanagement, Netzanschluss – alles aus einer Hand. Wir kennen alle Förderprogramme.</p>
        </div>
        <div class="service-card">
          <div class="service-icon">🏠</div>
          <h3>Smart Home</h3>
          <p>Automatisierung, Lichtsteuerung, Energiemonitoring – was wirklich sinnvoll ist (und was eher Spielerei bleibt).</p>
        </div>
        <div class="service-card">
          <div class="service-icon">🔌</div>
          <h3>Elektroinstallation</h3>
          <p>Ob neue Steckdose, Sicherungskasten oder komplette Unterverteilung – schnell, sauber, zuverlässig.</p>
        </div>
      </div>
      <div class="text-center" style="margin-top:1.5rem;">
        <NuxtLink to="/services" class="btn btn-outline">Alle Dienstleistungen →</NuxtLink>
      </div>
    </section>

    <!-- Feature Row -->
    <section class="section container">
      <div class="feature-row">
        <div class="feature-img">
          <img src="/img/smart-home.jpg" alt="Photovoltaik und erneuerbare Energien" />
        </div>
        <div class="feature-text">
          <h3>Erneuerbare Energien – von klein bis groß</h3>
          <p>
            Ob Balkonkraftwerk, Dach-PV mit Speicher oder Wärmepumpenanschluss: Wir begleiten Sie von der ersten Frage
            bis zur Inbetriebnahme. Inhabergeführt, herstellerunabhängig, ehrlich.
          </p>
          <NuxtLink to="/services" class="btn btn-warning">Zu den Leistungen →</NuxtLink>
        </div>
      </div>
    </section>

    <!-- USPs -->
    <section class="section container">
      <h2 class="text-center">Warum Elektro-Glaser?</h2>
      <div class="usp-row">
        <div class="usp-item">
          <div class="usp-icon">💶</div>
          <h4>Transparente Preise</h4>
          <p>Faire Angebote – optional mit Angabe, was Sie selbst erledigen dürfen.</p>
        </div>
        <div class="usp-item">
          <div class="usp-icon">🔓</div>
          <h4>Herstellerunabhängig</h4>
          <p>Wir empfehlen, was zu Ihnen passt – nicht, was uns die höchste Marge bringt.</p>
        </div>
        <div class="usp-item">
          <div class="usp-icon">🤝</div>
          <h4>Auch kleine Aufträge</h4>
          <p>Wir nehmen Aufträge an, für die sich andere Elektriker oft nicht finden lassen.</p>
        </div>
        <div class="usp-item">
          <div class="usp-icon">💡</div>
          <h4>Echte Beratung</h4>
          <p>Wir erklären, was Sinn macht – verständlich, ehrlich, ohne Fachchinesisch.</p>
        </div>
      </div>
    </section>
  </div>
</template>
