# CIT50100-final

gcloud functions deploy sendDeal \
--entry-point sendDeal \
--runtime nodejs18 \
--trigger-event "providers/cloud.firestore/eventTypes/document.create" \
--trigger-resource "projects/sp24-41200-antweyer-traveldeal/databases/(default)/documents/deals/{pushId}"


