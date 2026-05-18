---
title: Good Practices and Common Pitfalls in the Research and Development of New Electrolytes for Flow Batteries
keywords:
- flow batteries
- electrolytes
- research methodology
- best practices
lang: en-US
date-meta: '2026-05-18'
author-meta:
- Marc-Antoni Goulet
- Christian Stolze
- Solène Guihéneuf
- Steven Le Vot
- Edgar Ventosa
- Ulrich S. Schubert
- Fikile Brushett
- Michael J. Aziz
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Good Practices and Common Pitfalls in the Research and Development of New Electrolytes for Flow Batteries" />
  <meta name="citation_title" content="Good Practices and Common Pitfalls in the Research and Development of New Electrolytes for Flow Batteries" />
  <meta property="og:title" content="Good Practices and Common Pitfalls in the Research and Development of New Electrolytes for Flow Batteries" />
  <meta property="twitter:title" content="Good Practices and Common Pitfalls in the Research and Development of New Electrolytes for Flow Batteries" />
  <meta name="dc.date" content="2026-05-18" />
  <meta name="citation_publication_date" content="2026-05-18" />
  <meta property="article:published_time" content="2026-05-18" />
  <meta name="dc.modified" content="2026-05-18T21:03:39+00:00" />
  <meta property="article:modified_time" content="2026-05-18T21:03:39+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Marc-Antoni Goulet" />
  <meta name="citation_author_institution" content="Department of Chemical and Materials Engineering, Concordia University, Montreal, Quebec, Canada" />
  <meta name="citation_author" content="Christian Stolze" />
  <meta name="citation_author_institution" content="Laboratory of Organic and Macromolecular Chemistry (IOMC), Friedrich Schiller University Jena, Humboldtstraße 10, 07743 Jena, Germany" />
  <meta name="citation_author_institution" content="Center for Energy and Environmental Chemistry Jena (CEEC Jena), Friedrich Schiller University Jena, Philosophenweg 7a, 07743 Jena, Germany" />
  <meta name="citation_author_institution" content="Helmholtz-Institute for Polymers in Energy Applications Jena (HIPOLE Jena), Lessingstrasse 12–14, 07743 Jena, Germany" />
  <meta name="citation_author_institution" content="Helmholtz-Zentrum Berlin für Materialien und Energie (HZB), Hahn-Meitner-Platz 1, 14109 Berlin, Germany" />
  <meta name="citation_author_orcid" content="0000-0002-4620-8945" />
  <meta name="citation_author" content="Solène Guihéneuf" />
  <meta name="citation_author_institution" content="Kemiwatt, Rennes 35708, France" />
  <meta name="citation_author" content="Steven Le Vot" />
  <meta name="citation_author_institution" content="ICGM, University of Montpellier, CNRS, ENSCM, Montpellier 34095, France" />
  <meta name="citation_author_institution" content="Réseau sur le Stockage Electrochimique de l&#39;Energie (RS2E), CNRS, Amiens 80000, France" />
  <meta name="citation_author" content="Edgar Ventosa" />
  <meta name="citation_author_institution" content="Department of Chemistry, University of Burgos, Pza. Misael Bañuelos s/n, E-09001 Burgos, Spain" />
  <meta name="citation_author" content="Ulrich S. Schubert" />
  <meta name="citation_author_institution" content="Laboratory of Organic and Macromolecular Chemistry (IOMC), Friedrich Schiller University Jena, Humboldtstraße 10, 07743 Jena, Germany" />
  <meta name="citation_author_institution" content="Center for Energy and Environmental Chemistry Jena (CEEC Jena), Friedrich Schiller University Jena, Philosophenweg 7a, 07743 Jena, Germany" />
  <meta name="citation_author_institution" content="Helmholtz-Institute for Polymers in Energy Applications Jena (HIPOLE Jena), Lessingstrasse 12–14, 07743 Jena, Germany" />
  <meta name="citation_author_institution" content="Helmholtz-Zentrum Berlin für Materialien und Energie (HZB), Hahn-Meitner-Platz 1, 14109 Berlin, Germany" />
  <meta name="citation_author_orcid" content="0000-0003-2393-7889" />
  <meta name="citation_author" content="Fikile Brushett" />
  <meta name="citation_author_institution" content="Department of Chemical Engineering, Massachusetts Institute of Technology, Cambridge, Massachusetts 02139, United States of America" />
  <meta name="citation_author" content="Michael J. Aziz" />
  <meta name="citation_author_institution" content="Harvard John A. Paulson School of Engineering and Applied Sciences, Cambridge, Massachusetts 02138, United States of America" />
  <link rel="canonical" href="https://rfb-data-hub.github.io/guidelines-living-doc/" />
  <meta property="og:url" content="https://rfb-data-hub.github.io/guidelines-living-doc/" />
  <meta property="twitter:url" content="https://rfb-data-hub.github.io/guidelines-living-doc/" />
  <meta name="citation_fulltext_html_url" content="https://rfb-data-hub.github.io/guidelines-living-doc/" />
  <meta name="citation_pdf_url" content="https://rfb-data-hub.github.io/guidelines-living-doc/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://rfb-data-hub.github.io/guidelines-living-doc/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://rfb-data-hub.github.io/guidelines-living-doc/v/2fe80e835b014b2bb3a7ae6dc3f8423a81e9f3d2/" />
  <meta name="manubot_html_url_versioned" content="https://rfb-data-hub.github.io/guidelines-living-doc/v/2fe80e835b014b2bb3a7ae6dc3f8423a81e9f3d2/" />
  <meta name="manubot_pdf_url_versioned" content="https://rfb-data-hub.github.io/guidelines-living-doc/v/2fe80e835b014b2bb3a7ae6dc3f8423a81e9f3d2/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://rfb-data-hub.github.io/guidelines-living-doc/v/2fe80e835b014b2bb3a7ae6dc3f8423a81e9f3d2/))
was automatically generated
from [rfb-data-hub/guidelines-living-doc@2fe80e8](https://github.com/rfb-data-hub/guidelines-living-doc/tree/2fe80e835b014b2bb3a7ae6dc3f8423a81e9f3d2)
on May 18, 2026.
</em></small>



## Authors



+ **Marc-Antoni Goulet**
  <br>
  <small>
     Department of Chemical and Materials Engineering, Concordia University, Montreal, Quebec, Canada
  </small>

+ **Christian Stolze**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-4620-8945](https://orcid.org/0000-0002-4620-8945)
    <br>
  <small>
     Laboratory of Organic and Macromolecular Chemistry (IOMC), Friedrich Schiller University Jena, Humboldtstraße 10, 07743 Jena, Germany; Center for Energy and Environmental Chemistry Jena (CEEC Jena), Friedrich Schiller University Jena, Philosophenweg 7a, 07743 Jena, Germany; Helmholtz-Institute for Polymers in Energy Applications Jena (HIPOLE Jena), Lessingstrasse 12–14, 07743 Jena, Germany; Helmholtz-Zentrum Berlin für Materialien und Energie (HZB), Hahn-Meitner-Platz 1, 14109 Berlin, Germany
  </small>

+ **Solène Guihéneuf**
  <br>
  <small>
     Kemiwatt, Rennes 35708, France
  </small>

+ **Steven Le Vot**
  <br>
  <small>
     ICGM, University of Montpellier, CNRS, ENSCM, Montpellier 34095, France; Réseau sur le Stockage Electrochimique de l'Energie (RS2E), CNRS, Amiens 80000, France
  </small>

+ **Edgar Ventosa**
  <br>
  <small>
     Department of Chemistry, University of Burgos, Pza. Misael Bañuelos s/n, E-09001 Burgos, Spain
  </small>

+ **Ulrich S. Schubert**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-2393-7889](https://orcid.org/0000-0003-2393-7889)
    <br>
  <small>
     Laboratory of Organic and Macromolecular Chemistry (IOMC), Friedrich Schiller University Jena, Humboldtstraße 10, 07743 Jena, Germany; Center for Energy and Environmental Chemistry Jena (CEEC Jena), Friedrich Schiller University Jena, Philosophenweg 7a, 07743 Jena, Germany; Helmholtz-Institute for Polymers in Energy Applications Jena (HIPOLE Jena), Lessingstrasse 12–14, 07743 Jena, Germany; Helmholtz-Zentrum Berlin für Materialien und Energie (HZB), Hahn-Meitner-Platz 1, 14109 Berlin, Germany
  </small>

+ **Fikile Brushett**
  <br>
  <small>
     Department of Chemical Engineering, Massachusetts Institute of Technology, Cambridge, Massachusetts 02139, United States of America
  </small>

+ **Michael J. Aziz**
  ^[✉](#correspondence)^<br>
  <small>
     Harvard John A. Paulson School of Engineering and Applied Sciences, Cambridge, Massachusetts 02138, United States of America
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/rfb-data-hub/guidelines-living-doc/issues)
or email to
Michael J. Aziz \<\>.


:::


## Abstract {.page_break_before}




## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

