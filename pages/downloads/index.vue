<template>
  <div class="container">
    <div>
      <h1 class="title">
        Download Ubuntu 20.04 LTS and other versions
      </h1>
      <div>LTS means long term support. Downloading LTS versions is mostly recomended.</div> 
      <h2 class="subtitle">Ubuntu 20.04 LTS Daily Build (Alpha/Beta):</h2>
      <p><b>Download Ubuntu 20.04 LTS (Focal Fossa) Daily Build:</b> downloads are currently available from <a href="#" data-href="http://cdimage.ubuntu.com/daily-live/pending/" v-on:click="op">official Ubuntu website</a>.</p>
      <h2 class="subtitle">xUbuntu 18.04 LTS <span class="authors">Authors choose</span></h2>
      <p><b>xUbuntu</b> is official Ubuntu release with light weight XFCE interface in the box. Excellent for low performance machines (Laptop with Intel Atom, 1 Gb RAM for example).</p>
      <div><b>Download xUbuntu 18.04 LTS torrent:</b> <a href="/torrents/xubuntu-18.04.3-desktop-amd64.iso.torrent">xubuntu-18.04.3-desktop-amd64.iso.torrent</a></div>
      <h2 class="subtitle">xUbuntu 18.04 LTS (32-bit)</h2>
      <p>Ubuntu 18.04 Desktop doesn't official supports 32-bit platforms because of Gnome 3 etc. <b>xUbuntu 18.04</b> supports it well.</p>
      <div><b>Download xUbuntu 18.04 LTS (32-bit) torrent:</b> <a href="/torrents/xubuntu-18.04.3-desktop-i386.iso.torrent">xubuntu-18.04.3-desktop-i386.iso.torrent</a></div>
      <h2 class="subtitle">Ubuntu 18.04 Desktop LTS</h2>
      <p>Official desktop release. Most installed.</p>
      <div><b>Download Ubuntu 18.04 Desktop LTS torrent:</b> <a href="/torrents/ubuntu-18.04.3-desktop-amd64.iso.torrent">ubuntu-18.04.3-desktop-amd64.iso.torrent</a></div>
      <h2 class="subtitle">Ubuntu 18.04 Server LTS</h2>
      <p>Official server release. Most installed.</p>
      <div><b>Download Ubuntu 18.04 Server LTS torrent:</b> <a href="/torrents/ubuntu-18.04.3-live-server-amd64.iso.torrent">ubuntu-18.04.3-live-server-amd64.iso.torrent</a></div>
      <h2 class="subtitle">xUbuntu 19.04 (Latest)</h2>
      <p>It is not LTS version. Install for your own risk.</p>
      <div><b>Download xUbuntu 19.04 torrent:</b> <a href="/torrents/xubuntu-19.04-desktop-amd64.iso.torrent">xubuntu-19.04-desktop-amd64.iso.torrent</a></div>
      <h2 class="subtitle">Ubuntu 19.04 Desktop</h2>
      <p>It is not LTS version. Install for your own risk.</p>
      <div><b>Download Ubuntu 19.04 Desktop torrent:</b> <a href="/torrents/ubuntu-19.04-desktop-amd64.iso.torrent">ubuntu-19.04-desktop-amd64.iso.torrent</a></div>
      <h2 class="subtitle">Ubuntu 19.04 Server</h2>
      <p>It is not LTS version. Install for your own risk.</p>
      <div><b>Download Ubuntu 19.04 Server torrent:</b> <a href="/torrents/ubuntu-19.04-live-server-amd64.iso.torrent">ubuntu-19.04-desktop-amd64.iso.torrent</a></div>
      <h2 class="subtitle">Ubuntu 20.04 LTS</h2>
      <p>Official release: April 2020.</p>
      <div><b>Download Ubuntu 20.04 LTS torrent:</b> comming soon</div>
      <h2 class="subtitle">xUbuntu 20.04 LTS</h2>
      <p>Official release: April 2020 + few days</p>
      <div><b>Download xUbuntu 20.04 LTS torrent:</b> comming soon</div>
      <h2 class="subtitle">Ubuntu 20.04 Beta/Alpha</h2>
      <p>Alpha version will be publish in few weeks after 19.10 release.</p>
      <div><b>Download Ubuntu 20.04 LTS Alpha/Beta torrent:</b> as soon as possible</div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  head: {
    title: 'Download Ubuntu 20.04 | ubuntu.space'
  },
  methods: {
      op(op) {
      window.open(op.target.dataset.href);
    }
  }
}
</script>

<style>
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 35px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 36px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  padding-top: 48px;
}

.description {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    padding: 15px;
}

.links {
  padding-top: 15px;
}

.authors {
  color: #448b00;
}
</style>
