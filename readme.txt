--------------- Kubernetes Service Açıklamlar -------------

1- ClusterIp default service.yaml yazıldığında otomatik olarak oluşturulur ve internal yapıdadır.
2- NodePort service.yaml tanımlandığında otomatik olarak ClusterIp ataması yapar ve ayanı zamanıda service dışarıdan erişilebilir olur.
3- LoadBalancer service.yaml tanımlandığında dışarıdan güvenli bir şekilde içerideki NodePort'a erişim sağlanır aynı zamanda ClusterIp olarak da tanımlama yapılır.
