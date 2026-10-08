# Operaciones de Rapiboy

Consultar el schema de la herramienta descubierta para conocer los datos requeridos.

| Modalidad | Herramienta | Método y ruta | Permiso |
| --- | --- | --- | --- |
| NextDaySmart | `nextDaySmartPost` | `POST /v1/NextDaySmart/Post` | `rapiboy:write` |
| NextDaySmart | `nextDaySmartGet` | `GET /v1/NextDaySmart/Get` | `rapiboy:read` |
| NextDaySmart | `nextDaySmartGetQuery` | `GET /v1/NextDaySmart/GetQuery` | `rapiboy:read` |
| NextDaySmart | `nextDaySmartPut` | `PUT /v1/NextDaySmart/Put` | `rapiboy:write` |
| NextDaySmart | `nextDaySmartCancel` | `PUT /v1/NextDaySmart/Cancel` | `rapiboy:write` |
| NextDaySmart | `nextDaySmartGetList` | `GET /v1/NextDaySmart/GetList` | `rapiboy:read` |
| OnDemandSmart | `onDemandSmartConversionMercadoLibre` | `POST /v1/OnDemandSmart/ConversionMercadoLibre` | `rapiboy:write` |
| OnDemandSmart | `onDemandSmartPost` | `POST /v1/OnDemandSmart/Post` | `rapiboy:write` |
| OnDemandSmart | `onDemandSmartGet` | `GET /v1/OnDemandSmart/Get` | `rapiboy:read` |
| OnDemandSmart | `onDemandSmartGetQuery` | `GET /v1/OnDemandSmart/GetQuery` | `rapiboy:read` |
| OnDemandSmart | `onDemandSmartPut` | `PUT /v1/OnDemandSmart/Put` | `rapiboy:write` |
| OnDemandSmart | `onDemandSmartCancel` | `PUT /v1/OnDemandSmart/Cancel` | `rapiboy:write` |
| OnDemandSmart | `onDemandSmartGetList` | `GET /v1/OnDemandSmart/GetList` | `rapiboy:read` |
| OnDemandBasic | `onDemandBasicPost` | `POST /v1/OnDemandBasic/Post` | `rapiboy:write` |
| OnDemandBasic | `onDemandBasicGet` | `GET /v1/OnDemandBasic/Get` | `rapiboy:read` |
| OnDemandBasic | `onDemandBasicGetQuery` | `GET /v1/OnDemandBasic/GetQuery` | `rapiboy:read` |
| OnDemandBasic | `onDemandBasicPut` | `PUT /v1/OnDemandBasic/Put` | `rapiboy:write` |
| OnDemandBasic | `onDemandBasicCancel` | `PUT /v1/OnDemandBasic/Cancel` | `rapiboy:write` |
| OnDemandBasic | `onDemandBasicGetList` | `GET /v1/OnDemandBasic/GetList` | `rapiboy:read` |
| Food | `foodPost` | `POST /v1/Food/Post` | `rapiboy:write` |
| Food | `foodGet` | `GET /v1/Food/Get` | `rapiboy:read` |
| Food | `foodGetQuery` | `GET /v1/Food/GetQuery` | `rapiboy:read` |
| Food | `foodPut` | `PUT /v1/Food/Put` | `rapiboy:write` |
| Food | `foodCancel` | `PUT /v1/Food/Cancel` | `rapiboy:write` |
| Food | `foodGetList` | `GET /v1/Food/GetList` | `rapiboy:read` |
| Sims | `simsPost` | `POST /v1/Sims/Post` | `rapiboy:write` |
| Sims | `simsGet` | `GET /v1/Sims/Get` | `rapiboy:read` |
| Sims | `simsGetQuery` | `GET /v1/Sims/GetQuery` | `rapiboy:read` |
| Sims | `simsPut` | `PUT /v1/Sims/Put` | `rapiboy:write` |
| Sims | `simsCancel` | `PUT /v1/Sims/Cancel` | `rapiboy:write` |
| Sims | `simsGetList` | `GET /v1/Sims/GetList` | `rapiboy:read` |
| SaaS | `saaSPost` | `POST /v1/SaaS/Post` | `rapiboy:write` |
| SaaS | `saaSGet` | `GET /v1/SaaS/Get` | `rapiboy:read` |
| SaaS | `saaSGetQuery` | `GET /v1/SaaS/GetQuery` | `rapiboy:read` |
| SaaS | `saaSPut` | `PUT /v1/SaaS/Put` | `rapiboy:write` |
| SaaS | `saaSCancel` | `PUT /v1/SaaS/Cancel` | `rapiboy:write` |
| SaaS | `saaSGetList` | `GET /v1/SaaS/GetList` | `rapiboy:read` |
| NextDayBasic | `nextDayBasicPost` | `POST /v1/NextDayBasic/Post` | `rapiboy:write` |
| NextDayBasic | `nextDayBasicGet` | `GET /v1/NextDayBasic/Get` | `rapiboy:read` |
| NextDayBasic | `nextDayBasicGetQuery` | `GET /v1/NextDayBasic/GetQuery` | `rapiboy:read` |
| NextDayBasic | `nextDayBasicPut` | `PUT /v1/NextDayBasic/Put` | `rapiboy:write` |
| NextDayBasic | `nextDayBasicCancel` | `PUT /v1/NextDayBasic/Cancel` | `rapiboy:write` |
| NextDayBasic | `nextDayBasicGetList` | `GET /v1/NextDayBasic/GetList` | `rapiboy:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajePost` | `POST /v1/Viaje/Post` | `rapiboy:write` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajeGetQuery` | `GET /v1/Viaje/GetQuery` | `rapiboy:read` |
| Food | `foodRuta` | `POST /v1/Food/Ruta` | `rapiboy:write` |
| Food | `foodAsignarRuta` | `PUT /v1/Food/AsignarRuta` | `rapiboy:write` |
| Food | `foodQuitarRuta` | `PUT /v1/Food/QuitarRuta` | `rapiboy:write` |
| Food, OnDemandBasic | `foodGetReservas` | `GET /v1/Food/GetReservas` | `rapiboy:read` |
| Food, OnDemandBasic | `foodAsignarReserva` | `POST /v1/Food/AsignarReserva` | `rapiboy:write` |
| NextDaySmart | `nextDaySmartQr` | `GET /v1/NextDaySmart/Qr` | `rapiboy:read` |
| NextDaySmart | `nextDaySmartZpl` | `GET /v1/NextDaySmart/Zpl` | `rapiboy:read` |
| NextDaySmart | `nextDaySmartInfoRepa` | `GET /v1/NextDaySmart/InfoRepa` | `rapiboy:read` |
| NextDaySmart | `nextDaySmartCotizar` | `GET /v1/NextDaySmart/Cotizar` | `rapiboy:quote` |
| OnDemandBasic | `onDemandBasicCotizar` | `GET /v1/OnDemandBasic/Cotizar` | `rapiboy:quote` |
| OnDemandSmart, Food | `onDemandSmartCotizar` | `POST /v1/OnDemandSmart/Cotizar` | `rapiboy:quote` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajeEvidencias` | `GET /v1/Viaje/Evidencias` | `rapiboy:read` |
| NextDaySmart | `nextDaySmartEvidencias` | `GET /v1/NextDaySmart/Evidencias` | `rapiboy:read` |
| NextDayBasic | `nextDayBasicEvidencias` | `GET /v1/NextDayBasic/Evidencias` | `rapiboy:read` |
| OnDemandSmart | `onDemandSmartEvidencias` | `GET /v1/OnDemandSmart/Evidencias` | `rapiboy:read` |
| OnDemandBasic | `onDemandBasicEvidencias` | `GET /v1/OnDemandBasic/Evidencias` | `rapiboy:read` |
| Food | `foodEvidencias` | `GET /v1/Food/Evidencias` | `rapiboy:read` |
| SaaS | `saaSEvidencias` | `GET /v1/SaaS/Evidencias` | `rapiboy:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `lastMileEstados` | `GET /v1/LastMile/Estados` | `rapiboy:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `lastMileMotivosCancelado` | `GET /v1/LastMile/MotivosCancelado` | `rapiboy:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `lastMileMotivosNoEntregado` | `GET /v1/LastMile/MotivosNoEntregado` | `rapiboy:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `lastMileVehiculos` | `GET /v1/LastMile/Vehiculos` | `rapiboy:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajeGet` | `GET /v1/Viaje/Get` | `rapiboy:read` |
| NextDaySmart, OnDemandSmart, OnDemandBasic, Food, Sims, SaaS, NextDayBasic | `viajeCancel` | `PUT /v1/Viaje/Cancel` | `rapiboy:write` |
| Food | `foodTracking` | `GET /v1/Food/Tracking` | `rapiboy:read` |
