<h1>Disloman Kubernetes Manifests Objects</h1>

<p>
<h3>Per il deployment su Minikube assicurarsi che i seguenti addons siano abilitati: </h3>
    <ul>
        <li>ingress</li>
        <li>dashboard</li>
        <li>storage-provider</li>
        <li>metrics-server</li>
        <li>heapster</li>
    </ul>
</p>

<p>
<h3>La lista che segue descrive l'ordine da seguire per la creazione da nuovo del cluster con tutti i Kubernetes Manifest Objects
attraverso il comando "<code>kubectl create -f &lt;manifest-file.yml&gt;</code>"</h3>
<ol>
    <li>Namespaces Directory</li>
    <li>Developments/Configmap Directory</li>
    <li>Policies Directory</li>
    <li>StorageClasses Directory</li>
    <li>Creare il Kubernetes Secret seguendo i comandi descritti in "Developments/Ingress/TLS/Kubernetes Secret HTTPS Ingress Connection Creation.txt"
    <li>Developments/Ingress/TLS/ingress-disloman.yml</li>
    <li>Developments/StatefulSet&Svc Directory(Zookeeper,Kafka,MongoDB)</li>
    <li>Developments/Deploy&Svc Directory</li> 
</ol
</p>
