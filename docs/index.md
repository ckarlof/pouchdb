---
layout: default
title: PouchDB, the JavaScript Database that Syncs!
---

# The Database that Syncs!

<div id="home1">
  <section>
    <p>PouchDB is a small embedable Database written in Javascript and inspired by Apache CouchDB,
      it allows your application to store data locally so your applications always work
      even while offline and syncs that data online transparently so your users always
      have most up to date data possible. </p>
  </section>
  <section>
    <button id="download">
      Download Latest Stable<br />
      <small>(pouchdb-0.1.0.js 51KB)</small>
    </button><br />
    <a href="/">Learn More</a>
  </section>
</div>

<div id="home2">
  <section>
    <h2>Install</h2>
    <code>&lt;script src="pouchdb.js"&gt;&lt;/script&gt;</code>
    <h5 style="text-align:center">or</h5>
    <code>npm install pouchdb</code>
  </section>
  <section>
    <h2>Save Data</h2>
    <pre><code>var db = new Pouch('mydatabase');

db.put({
 some: 'data',
 random: 'json'
});</code></pre>
  </section>
  <section>
    <h2>Sync!</h2>
    <pre><code>var remote = 'http://a.com/mydb';
db.replicate.to(remote);
db.replicate.from(remote);</code></pre>
  </section>
</div>

## Blog Posts

### PouchDB 0.1.0 Released.
