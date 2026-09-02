# Taxi Central Android

Proyecto Android con tres aplicaciones conectadas al mismo backend Supabase:

- Taxi Cliente (`uy.taxicentral.cliente`)
- Taxi Conductor (`uy.taxicentral.conductor`)
- Taxi Central (`uy.taxicentral.central`)

La app Cliente permite dirección manual, GPS y selección exacta del punto en OpenStreetMap.
La app Conductor usa Supabase Realtime en primer plano y un servicio Android persistente cuando está Disponible para avisar nuevos pedidos con sonido y vibración.

Los APK se generan automáticamente mediante GitHub Actions.
