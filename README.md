# artshowparis2025
Landing Page for the ArtShow Paris 2025


## OVH DNS

For Vercel domain, do the following steps : 

 - Step 1 : add a DNS entry 
    - Type : TXT
    - Sous-domaine : _vercel (exactement comme ça, avec le underscore)
    - TTL : "Par défaut"
    - Valeur : vc-domain-verify=XXXX ===> Ce que dit Vercel dans son dashboard "Domain verification"

- Step 2 : 

    - Type : CNAME
    - Sous-domaine : <new_subdomain> (sans le .inrealart.com)
    - TTL : "Par défaut"
    - Cible : cname.vercel-dns.com. (n'oubliez pas le point à la fin)

