Smart Catalogue System 

A product for preparing a false positive dynamic catalogue for stores by analysing the order details from bill receipts. The catalogue will be prepared based on the extracted details from the image document by using OCR and ML Algo’s without any outliers.


For running parese 

sudo docker build -f DockerParser -t parse .

sudo docker run --rm -d parser



For running UI

sudo docker build -f DockerUI -t ui .

sudo docker run --rm -d ui
