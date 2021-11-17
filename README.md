# OAUTH 2.0
El proyecto contiene la implementación del protocolo de autorización OAuth2.0 utilizado por las APIs para comunicarse con la PDE.  Utiliza el grant_type password e implementa el flujo de refresh_token, acorde a las especificaciones emitidas por la PDN, basandose en el uso de JWT para el control y administración de los tokens.

Esta desarrollado en .netcore  3.1 con IdentityServer4

Este proyecto forma parte de una solución que contempla las APIs del S1, S2 y S3 en ambiente de desarrollo, para reproducirlo completamente, se sugiere el siguiente orden:

Instalación: preparación del ambiente de desarrollo.

OAuth2.0: implementación del protocolo de autorización.
API S1: API para conectarse a la PDN en el Sistema 1.
API S2: API para conectarse a la PDN en el Sistema 2.
API S3S: API para conectarse a la PDN en el Sistema 3 Servidores sancionados.
API S3P: API para conectarse a la PDN en el Sistema 3 Particulares Sancionados.

# Documentación

<a href="https://docs.google.com/document/d/1UoUKII1dscdKojGMEdUyLls0CKPp4pe2E28djCYMf6A/edit">Documentación OAuth2.0</a></br>
<a href="https://identityserver4.readthedocs.io/en/latest/">Documentación IdentityServer4</a></br>
<a href="https://dotnet.microsoft.com/download/dotnet/3.1">.NETCORE 3.1</a>
