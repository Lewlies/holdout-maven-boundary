# holdout-maven-boundary

Repositorio sintético del conjunto de reserva (*hold-out*) del TFG *Análisis automatizado de vulnerabilidades en dependencias de software*. No contiene código, solo el manifiesto de dependencias.

No se usó para diseñar sca-gate. El ground truth (`ground_truth.yaml`) se escribió antes de ejecutar la herramienta sobre él.

| Dimensión | Paquete | Identificador |
|---|---|---|
| borde, lado vulnerable (2.13.2, corregido en 2.13.2.1) | com.fasterxml.jackson.core:jackson-databind | CVE-2020-36518 |
| borde, lado corregido (primera version sin los cuatro CVE de 2021) | org.apache.commons:commons-compress 1.21 | CVE-2021-35515 |
