# Qsurf
Qsurf: a software package for compressed QMC integration on parametric surfaces 
The main folder contains the following files:

- demo_CQMC_sphpoly: In this demo we compute a cubature rule over spherical polygons via QMC rules. Once the domain is available, we compute a full rule QMC and a compressed one, say CQMC, sharing the same integrals for polynomials up to a total degree.
- demo_CQMC_torus: same as above on a subdomain of a toroidal surface;
- demo_CQMC_franke: same as above on a subdomain of a surface given by Franke's function.
- pts_domain: corresponds to items (i) and (ii) of Algorithm Qsurf (see attached paper);
- cqmc_v2: corresponds to items (iii) and (vi) of Algorithm Qsurf (see attached paper);
- dCHEBVAND_v2: basis selection in item (iii) of Algorithm Qsurf (see attached paper);
- lawsonhanson, LHDM: NNLS implementation;
- dCATCH, implements Caratheodory-like compression via NNLS.
