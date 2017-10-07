# spid-passport
Passport authentication provider for SPID

Esiste già un provider per SAML: https://github.com/bergie/passport-saml

Un provider SPID per Passport dovrebbe basarsi su passport-saml se possibile (senza fork, ma usandolo come dipendenza), fornendolo preconfigurato per SPID e inoltre facilitando l'integrazione del bottone di login nella posizione desiderata

Esiste anche un ottimo modulo per Node che non usa Passport: https://github.com/Clever/saml2
Domanda: conviene fare (anche?) un'implementazione di SPID per Node senza Passport?
