+---------------------------+----------------+--------+-----------------------------+
|    Description            | Transport      | Port   | Application protocol        |
+---------------------------+----------------+--------+-----------------------------+
| Control plane             | QUIC/SCION     | 30256  | gRPC (Prefix discovery)     |
+---------------------------+----------------+--------+-----------------------------+
| Probe plane               | UDP/SCION      | 30856  | Custom probe encapsulation  |
+---------------------------+----------------+--------+-----------------------------+
| Underlay data-plane       | UDP/SCION      | 30056  | none                        |
+---------------------------+----------------+--------+-----------------------------+
| Monitoring                | TCP            | 30456  | HTTP/2                      |
+---------------------------+----------------+--------+-----------------------------+
