# Operaciones de Rapilog

Consultar el schema de la herramienta descubierta para conocer los datos requeridos.

| Modalidad | Herramienta | Método y ruta | Permiso |
| --- | --- | --- | --- |
| NextDaySmart | `nextDaySmartPost` | `POST /v1/NextDaySmart/Post` | `rapilog:write` |
| NextDaySmart | `nextDaySmartGet` | `GET /v1/NextDaySmart/Get` | `rapilog:read` |
| NextDaySmart | `nextDaySmartGetQuery` | `GET /v1/NextDaySmart/GetQuery` | `rapilog:read` |
| NextDaySmart | `nextDaySmartPut` | `PUT /v1/NextDaySmart/Put` | `rapilog:write` |
| NextDaySmart | `nextDaySmartCancel` | `PUT /v1/NextDaySmart/Cancel` | `rapilog:write` |
| NextDaySmart | `nextDaySmartGetList` | `GET /v1/NextDaySmart/GetList` | `rapilog:read` |
| OnDemandSmart | `onDemandSmartPost` | `POST /v1/OnDemandSmart/Post` | `rapilog:write` |
| OnDemandSmart | `onDemandSmartGet` | `GET /v1/OnDemandSmart/Get` | `rapilog:read` |
| OnDemandSmart | `onDemandSmartGetQuery` | `GET /v1/OnDemandSmart/GetQuery` | `rapilog:read` |
| OnDemandSmart | `onDemandSmartPut` | `PUT /v1/OnDemandSmart/Put` | `rapilog:write` |
| OnDemandSmart | `onDemandSmartCancel` | `PUT /v1/OnDemandSmart/Cancel` | `rapilog:write` |
| OnDemandSmart | `onDemandSmartGetList` | `GET /v1/OnDemandSmart/GetList` | `rapilog:read` |
| OnDemandBasic | `onDemandBasicPost` | `POST /v1/OnDemandBasic/Post` | `rapilog:write` |
| OnDemandBasic | `onDemandBasicGet` | `GET /v1/OnDemandBasic/Get` | `rapilog:read` |
| OnDemandBasic | `onDemandBasicGetQuery` | `GET /v1/OnDemandBasic/GetQuery` | `rapilog:read` |
| OnDemandBasic | `onDemandBasicPut` | `PUT /v1/OnDemandBasic/Put` | `rapilog:write` |
| OnDemandBasic | `onDemandBasicCancel` | `PUT /v1/OnDemandBasic/Cancel` | `rapilog:write` |
| OnDemandBasic | `onDemandBasicGetList` | `GET /v1/OnDemandBasic/GetList` | `rapilog:read` |
| Food | `foodPost` | `POST /v1/Food/Post` | `rapilog:write` |
| Food | `foodGet` | `GET /v1/Food/Get` | `rapilog:read` |
| Food | `foodGetQuery` | `GET /v1/Food/GetQuery` | `rapilog:read` |
| Food | `foodPut` | `PUT /v1/Food/Put` | `rapilog:write` |
| Food | `foodCancel` | `PUT /v1/Food/Cancel` | `rapilog:write` |
| Food | `foodGetList` | `GET /v1/Food/GetList` | `rapilog:read` |
| Sims | `simsPost` | `POST /v1/Sims/Post` | `rapilog:write` |
| Sims | `simsGet` | `GET /v1/Sims/Get` | `rapilog:read` |
| Sims | `simsGetQuery` | `GET /v1/Sims/GetQuery` | `rapilog:read` |
| Sims | `simsPut` | `PUT /v1/Sims/Put` | `rapilog:write` |
| Sims | `simsCancel` | `PUT /v1/Sims/Cancel` | `rapilog:write` |
| Sims | `simsGetList` | `GET /v1/Sims/GetList` | `rapilog:read` |
| SaaS | `saaSPost` | `POST /v1/SaaS/Post` | `rapilog:write` |
| SaaS | `saaSGet` | `GET /v1/SaaS/Get` | `rapilog:read` |
| SaaS | `saaSGetQuery` | `GET /v1/SaaS/GetQuery` | `rapilog:read` |
| SaaS | `saaSPut` | `PUT /v1/SaaS/Put` | `rapilog:write` |
| SaaS | `saaSCancel` | `PUT /v1/SaaS/Cancel` | `rapilog:write` |
| SaaS | `saaSGetList` | `GET /v1/SaaS/GetList` | `rapilog:read` |
| NextDayBasic | `nextDayBasicPost` | `POST /v1/NextDayBasic/Post` | `rapilog:write` |
| NextDayBasic | `nextDayBasicGet` | `GET /v1/NextDayBasic/Get` | `rapilog:read` |
| NextDayBasic | `nextDayBasicGetQuery` | `GET /v1/NextDayBasic/GetQuery` | `rapilog:read` |
| NextDayBasic | `nextDayBasicPut` | `PUT /v1/NextDayBasic/Put` | `rapilog:write` |
| NextDayBasic | `nextDayBasicCancel` | `PUT /v1/NextDayBasic/Cancel` | `rapilog:write` |
| NextDayBasic | `nextDayBasicGetList` | `GET /v1/NextDayBasic/GetList` | `rapilog:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajePost` | `POST /v1/Viaje/Post` | `rapilog:write` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajeGetQuery` | `GET /v1/Viaje/GetQuery` | `rapilog:read` |
| Food | `foodRuta` | `POST /v1/Food/Ruta` | `rapilog:write` |
| Food | `foodAsignarRuta` | `PUT /v1/Food/AsignarRuta` | `rapilog:write` |
| Food | `foodQuitarRuta` | `PUT /v1/Food/QuitarRuta` | `rapilog:write` |
| Food, OnDemandBasic | `foodGetReservas` | `GET /v1/Food/GetReservas` | `rapilog:read` |
| Food, OnDemandBasic | `foodAsignarReserva` | `POST /v1/Food/AsignarReserva` | `rapilog:write` |
| NextDaySmart | `nextDaySmartQr` | `GET /v1/NextDaySmart/Qr` | `rapilog:read` |
| NextDaySmart | `nextDaySmartZpl` | `GET /v1/NextDaySmart/Zpl` | `rapilog:read` |
| NextDaySmart | `nextDaySmartInfoRepa` | `GET /v1/NextDaySmart/InfoRepa` | `rapilog:read` |
| NextDaySmart | `nextDaySmartCotizar` | `GET /v1/NextDaySmart/Cotizar` | `rapilog:quote` |
| OnDemandBasic | `onDemandBasicCotizar` | `GET /v1/OnDemandBasic/Cotizar` | `rapilog:quote` |
| OnDemandSmart, Food | `onDemandSmartCotizar` | `POST /v1/OnDemandSmart/Cotizar` | `rapilog:quote` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajeEvidencias` | `GET /v1/Viaje/Evidencias` | `rapilog:read` |
| NextDaySmart | `nextDaySmartEvidencias` | `GET /v1/NextDaySmart/Evidencias` | `rapilog:read` |
| NextDayBasic | `nextDayBasicEvidencias` | `GET /v1/NextDayBasic/Evidencias` | `rapilog:read` |
| OnDemandSmart | `onDemandSmartEvidencias` | `GET /v1/OnDemandSmart/Evidencias` | `rapilog:read` |
| OnDemandBasic | `onDemandBasicEvidencias` | `GET /v1/OnDemandBasic/Evidencias` | `rapilog:read` |
| Food | `foodEvidencias` | `GET /v1/Food/Evidencias` | `rapilog:read` |
| SaaS | `saaSEvidencias` | `GET /v1/SaaS/Evidencias` | `rapilog:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `lastMileEstados` | `GET /v1/LastMile/Estados` | `rapilog:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `lastMileMotivosCancelado` | `GET /v1/LastMile/MotivosCancelado` | `rapilog:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `lastMileMotivosNoEntregado` | `GET /v1/LastMile/MotivosNoEntregado` | `rapilog:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `lastMileVehiculos` | `GET /v1/LastMile/Vehiculos` | `rapilog:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajeGet` | `GET /v1/Viaje/Get` | `rapilog:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajeCancel` | `PUT /v1/Viaje/Cancel` | `rapilog:write` |
| Food | `foodTracking` | `GET /v1/Food/Tracking` | `rapilog:read` |
