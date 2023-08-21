---
description: Competency Questions answers
cover: .gitbook/assets/360_F_434949006_MtUycXdKs8P4Qg6ElGkuP9UdsEX012YE.jpeg
coverY: 0
---

# ❓ CQ answers

### 1 - Name of the observer is Story 1?

```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX bias: <http://www.semanticweb.org/bias#>
SELECT ?subject
    WHERE { ?subject a bias:Observer}

```

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption><p>CQ 1</p></figcaption></figure>

***

### 2 - Which bias does Sarah exhibits?

```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX bias: <http://www.semanticweb.org/bias#>
SELECT ?subject
    WHERE { bias:Sarah  bias:exhibitsBias ?subject }
```

<figure><img src=".gitbook/assets/image (5).png" alt=""><figcaption><p>CQ 2</p></figcaption></figure>

***

### 3 - Which information confirms her bias?

<pre><code>PREFIX rdf: &#x3C;http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: &#x3C;http://www.w3.org/2002/07/owl#>
PREFIX rdfs: &#x3C;http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: &#x3C;http://www.w3.org/2001/XMLSchema#>
PREFIX bias: &#x3C;http://www.semanticweb.org/bias#>
SELECT ?subject
<strong>    WHERE { bias:Sarah  bias: confirmsBelief ?subject }
</strong></code></pre>

<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption><p>CQ 3</p></figcaption></figure>

***

### 4 - She holds belief about?

<pre><code>PREFIX rdf: &#x3C;http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: &#x3C;http://www.w3.org/2002/07/owl#>
PREFIX rdfs: &#x3C;http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: &#x3C;http://www.w3.org/2001/XMLSchema#>
PREFIX bias: &#x3C;http://www.semanticweb.org/bias#>
SELECT ?subject
<strong>    WHERE { bias:Sarah  bias:holdsBelief ?subject }
</strong></code></pre>

<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption><p>CQ 4</p></figcaption></figure>

***

### 5 - Which information she encountered?

```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX bias: <http://www.semanticweb.org/bias#>
SELECT ?subject
    WHERE { bias:Sarah  bias:encountersInformation ?subject }

```

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption><p>CQ 5</p></figcaption></figure>

***

### 6 - Name of the characters in Story 2?

```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX bias: <http://www.semanticweb.org/bias#>
SELECT ?subject
    WHERE { ?subject a bias:Character }
```

<figure><img src=".gitbook/assets/image (9).png" alt=""><figcaption><p>CQ 6</p></figcaption></figure>

***

### 7 - List all the generalities in Story 2?

```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX bias: <http://www.semanticweb.org/bias#>
SELECT ?subject
    WHERE {?subject a bias:Generalities} 
```

<figure><img src=".gitbook/assets/image (10).png" alt=""><figcaption><p>CQ 7</p></figcaption></figure>

***

### 8 - Name of the bias does John exhibits in story 2?

```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX bias: <http://www.semanticweb.org/bias#>
SELECT ?subject
    WHERE { bias:John  bias:exhibitsBias ?subject }
```

<figure><img src=".gitbook/assets/image (11).png" alt=""><figcaption><p>CQ 8</p></figcaption></figure>

***

### 9 - What is the observation in story 2?

```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX bias: <http://www.semanticweb.org/bias#>
SELECT ?subject
    WHERE {?subject a bias:Observations}
```

<figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption><p>CQ 9</p></figcaption></figure>

***

### 10 - What are some specifics in Story 2?

```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX bias: <http://www.semanticweb.org/bias#>
SELECT ?subject
    WHERE { ?subject rdfs:subClassOf bias:Specifics}
```

<figure><img src=".gitbook/assets/image (13).png" alt=""><figcaption><p>CQ 10</p></figcaption></figure>
