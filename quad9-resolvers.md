# quad9-resolvers

This file contains the most common Quad9 DNS stamps for filtered/unfiltered/ecs-filtered/ecs-unfiltered dnscrypt/doh services.

This is not a complete list of all available Quad9 stamps. These stamps support the DNSCrypt and DNS-over-HTTPS protocols which are the most commonly supported among DNS programs.

A complete list of Quad9 stamps including DNSCrypt, DoH, DoT, and Plain can be found at https://www.quad9.net/dnscrypt/

This list is maintained by support <@ quad9 [.] net>

To use this list, add this to the `[sources]` section of your `dnscrypt-proxy.toml` configuration file:

    [sources.quad9-resolvers]
    urls = ["https://quad9.net/dnscrypt/quad9-resolvers.md", "https://raw.githubusercontent.com/Quad9DNS/dnscrypt-settings/main/dnscrypt/quad9-resolvers.md"]
    minisign_key = "RWQBphd2+f6eiAqBsvDZEBXBGHQBJfeG6G+wJPPKxCZMoEQYpmoysKUN"
    cache_file = "quad9-resolvers.md"
    refresh_delay = 72
    prefix = "quad9-"

--

## dnscrypt-ip4-filter-pri
Quad9 (anycast) dnssec/no-log/filter 9.9.9.9
sdns://AQMAAAAAAAAADDkuOS45Ljk6ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## dnscrypt-ip4-filter-alt
Quad9 (anycast) dnssec/no-log/filter 149.112.112.9
sdns://AQMAAAAAAAAAEjE0OS4xMTIuMTEyLjk6ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## dnscrypt-ip4-filter-alt2
Quad9 (anycast) dnssec/no-log/filter 149.112.112.112
sdns://AQMAAAAAAAAAFDE0OS4xMTIuMTEyLjExMjo4NDQzIGfIR7jIdYzRICRVQ751Z0bfNN8dhMALjEcDaN-CHYY-GTIuZG5zY3J5cHQtY2VydC5xdWFkOS5uZXQ

## dnscrypt-ip6-filter-pri
Quad9 (anycast) dnssec/no-log/filter 2620:fe::fe
sdns://AQMAAAAAAAAAElsyNjIwOmZlOjpmZV06ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## dnscrypt-ip6-filter-alt
Quad9 (anycast) dnssec/no-log/filter 2620:fe::9
sdns://AQMAAAAAAAAAEVsyNjIwOmZlOjo5XTo4NDQzIGfIR7jIdYzRICRVQ751Z0bfNN8dhMALjEcDaN-CHYY-GTIuZG5zY3J5cHQtY2VydC5xdWFkOS5uZXQ

## dnscrypt-ip6-filter-alt2
Quad9 (anycast) dnssec/no-log/filter 2620:fe::fe:9
sdns://AQMAAAAAAAAAFFsyNjIwOmZlOjpmZTo5XTo4NDQzIGfIR7jIdYzRICRVQ751Z0bfNN8dhMALjEcDaN-CHYY-GTIuZG5zY3J5cHQtY2VydC5xdWFkOS5uZXQ

## dnscrypt-ip4-nofilter-pri
Quad9 (anycast) no-dnssec/no-log/no-filter 9.9.9.10
sdns://AQYAAAAAAAAADTkuOS45LjEwOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA

## dnscrypt-ip4-nofilter-alt
Quad9 (anycast) no-dnssec/no-log/no-filter 149.112.112.10
sdns://AQYAAAAAAAAAEzE0OS4xMTIuMTEyLjEwOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA

## dnscrypt-ip6-nofilter-pri
Quad9 (anycast) no-dnssec/no-log/no-filter 2620:fe::10
sdns://AQYAAAAAAAAAElsyNjIwOmZlOjoxMF06ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## dnscrypt-ip6-nofilter-alt
Quad9 (anycast) no-dnssec/no-log/no-filter 2620:fe::fe:10
sdns://AQYAAAAAAAAAFVsyNjIwOmZlOjpmZToxMF06ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## dnscrypt-ip4-filter-ecs-pri
Quad9 (anycast) dnssec/no-log/filter/ecs 9.9.9.11
sdns://AQMAAAAAAAAADTkuOS45LjExOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA

## dnscrypt-ip4-filter-ecs-alt
Quad9 (anycast) dnssec/no-log/filter/ecs 149.112.112.11
sdns://AQMAAAAAAAAAEzE0OS4xMTIuMTEyLjExOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA

## dnscrypt-ip6-filter-ecs-pri
Quad9 (anycast) dnssec/no-log/filter/ecs 2620:fe::11
sdns://AQMAAAAAAAAAElsyNjIwOmZlOjoxMV06ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## dnscrypt-ip6-filter-ecs-alt
Quad9 (anycast) dnssec/no-log/filter/ecs 2620:fe::fe:11
sdns://AQMAAAAAAAAAFVsyNjIwOmZlOjpmZToxMV06ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## dnscrypt-ip4-nofilter-ecs-pri
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 9.9.9.12
sdns://AQYAAAAAAAAADTkuOS45LjEyOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA

## dnscrypt-ip4-nofilter-ecs-alt
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 149.112.112.12
sdns://AQYAAAAAAAAAEzE0OS4xMTIuMTEyLjEyOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA

## dnscrypt-ip6-nofilter-ecs-pri
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 2620:fe::12
sdns://AQYAAAAAAAAAElsyNjIwOmZlOjoxMl06ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## dnscrypt-ip6-nofilter-ecs-alt 
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 2620:fe::fe:12 
sdns://AQYAAAAAAAAAFVsyNjIwOmZlOjpmZToxMl06ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## doh-ip4-port443-filter-pri
Quad9 (anycast) dnssec/no-log/filter 9.9.9.9
sdns://AgMAAAAAAAAABzkuOS45LjkgKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoSZG5zOS5xdWFkOS5uZXQ6NDQzCi9kbnMtcXVlcnk

## doh-ip4-port5053-filter-pri
Quad9 (anycast) dnssec/no-log/filter 9.9.9.9
sdns://AgMAAAAAAAAABzkuOS45LjkgKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zOS5xdWFkOS5uZXQ6NTA1MwovZG5zLXF1ZXJ5

## doh-ip4-port443-filter-alt
Quad9 (anycast) dnssec/no-log/filter 149.112.112.9
sdns://AgMAAAAAAAAADTE0OS4xMTIuMTEyLjkgKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoSZG5zOS5xdWFkOS5uZXQ6NDQzCi9kbnMtcXVlcnk

## doh-ip4-port5053-filter-alt
Quad9 (anycast) dnssec/no-log/filter 149.112.112.9
sdns://AgMAAAAAAAAADTE0OS4xMTIuMTEyLjkgKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zOS5xdWFkOS5uZXQ6NTA1MwovZG5zLXF1ZXJ5

## doh-ip4-port443-filter-alt2
Quad9 (anycast) dnssec/no-log/filter 149.112.112.112
sdns://AgMAAAAAAAAADzE0OS4xMTIuMTEyLjExMiAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihFkbnMucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5

## doh-ip4-port5053-filter-alt2
Quad9 (anycast) dnssec/no-log/filter 149.112.112.112
sdns://AgMAAAAAAAAADzE0OS4xMTIuMTEyLjExMiAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihJkbnMucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ

## doh-ip6-port443-filter-pri
Quad9 (anycast) dnssec/no-log/filter 2620:fe::fe
sdns://AgMAAAAAAAAADVsyNjIwOmZlOjpmZV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoRZG5zLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ

## doh-ip6-port5053-filter-pri
Quad9 (anycast) dnssec/no-log/filter 2620:fe::fe
sdns://AgMAAAAAAAAADVsyNjIwOmZlOjpmZV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoSZG5zLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk

## doh-ip6-port443-filter-alt
Quad9 (anycast) dnssec/no-log/filter 2620:fe::9
sdns://AgMAAAAAAAAADFsyNjIwOmZlOjo5XSAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihFkbnMucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5

## doh-ip6-port5053-filter-alt
Quad9 (anycast) dnssec/no-log/filter 2620:fe::9
sdns://AgMAAAAAAAAADFsyNjIwOmZlOjo5XSAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihJkbnMucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ

## doh-ip6-port443-filter-alt2
Quad9 (anycast) dnssec/no-log/filter 2620:fe::fe:9
sdns://AgMAAAAAAAAAD1syNjIwOmZlOjpmZTo5XSAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihJkbnM5LnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ

## doh-ip6-port5053-filter-alt2
Quad9 (anycast) dnssec/no-log/filter 2620:fe::fe:9
sdns://AgMAAAAAAAAAD1syNjIwOmZlOjpmZTo5XSAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihNkbnM5LnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk

## doh-ip4-port443-nofilter-pri
Quad9 (anycast) no-dnssec/no-log/no-filter 9.9.9.10
sdns://AgYAAAAAAAAACDkuOS45LjEwICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczEwLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ

## doh-ip4-port5053-nofilter-pri
Quad9 (anycast) no-dnssec/no-log/no-filter 9.9.9.10
sdns://AgYAAAAAAAAACDkuOS45LjEwICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczEwLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk

## doh-ip4-port443-nofilter-alt
Quad9 (anycast) no-dnssec/no-log/no-filter 149.112.112.10
sdns://AgYAAAAAAAAADjE0OS4xMTIuMTEyLjEwICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczEwLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ

## doh-ip4-port5053-nofilter-alt
Quad9 (anycast) no-dnssec/no-log/no-filter 149.112.112.10
sdns://AgYAAAAAAAAADjE0OS4xMTIuMTEyLjEwICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczEwLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk

## doh-ip6-port443-nofilter-pri
Quad9 (anycast) no-dnssec/no-log/no-filter 2620:fe::10
sdns://AgYAAAAAAAAADVsyNjIwOmZlOjoxMF0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTAucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5

## doh-ip6-port5053-nofilter-pri
Quad9 (anycast) no-dnssec/no-log/no-filter 2620:fe::10
sdns://AgYAAAAAAAAADVsyNjIwOmZlOjoxMF0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTAucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ

## doh-ip6-port443-nofilter-alt
Quad9 (anycast) no-dnssec/no-log/no-filter 2620:fe::fe:10
sdns://AgYAAAAAAAAAEFsyNjIwOmZlOjpmZToxMF0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTAucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5

## doh-ip6-port5053-nofilter-alt
Quad9 (anycast) no-dnssec/no-log/no-filter 2620:fe::fe:10
sdns://AgYAAAAAAAAAEFsyNjIwOmZlOjpmZToxMF0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTAucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ

## doh-ip4-port443-filter-ecs-pri
Quad9 (anycast) dnssec/no-log/filter/ecs 9.9.9.11
sdns://AgMAAAAAAAAACDkuOS45LjExICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczExLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ

## doh-ip4-port5053-filter-ecs-pri
Quad9 (anycast) dnssec/no-log/filter/ecs 9.9.9.11
sdns://AgMAAAAAAAAACDkuOS45LjExICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczExLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk

## doh-ip4-port443-filter-ecs-alt
Quad9 (anycast) dnssec/no-log/filter/ecs 149.112.112.11
sdns://AgMAAAAAAAAADjE0OS4xMTIuMTEyLjExICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczExLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ

## doh-ip4-port5053-filter-ecs-alt
Quad9 (anycast) dnssec/no-log/filter/ecs 149.112.112.11
sdns://AgMAAAAAAAAADjE0OS4xMTIuMTEyLjExICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczExLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk

## doh-ip6-port443-filter-ecs-pri
Quad9 (anycast) dnssec/no-log/filter/ecs 2620:fe::11
sdns://AgMAAAAAAAAADVsyNjIwOmZlOjoxMV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTEucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5

## doh-ip6-port5053-filter-ecs-pri
Quad9 (anycast) dnssec/no-log/filter/ecs 2620:fe::11
sdns://AgMAAAAAAAAADVsyNjIwOmZlOjoxMV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTEucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ

## doh-ip6-port443-filter-ecs-alt
Quad9 (anycast) dnssec/no-log/filter/ecs 2620:fe::fe:11
sdns://AgMAAAAAAAAAEFsyNjIwOmZlOjpmZToxMV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTEucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5

## doh-ip6-port5053-filter-ecs-alt
Quad9 (anycast) dnssec/no-log/filter/ecs 2620:fe::fe:11
sdns://AgMAAAAAAAAAEFsyNjIwOmZlOjpmZToxMV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTEucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ

## doh-ip4-port443-nofilter-ecs-pri
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 9.9.9.12
sdns://AgYAAAAAAAAACDkuOS45LjEyICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczEyLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ

## doh-ip4-port5053-nofilter-ecs-pri
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 9.9.9.12
sdns://AgYAAAAAAAAACDkuOS45LjEyICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczEyLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk

## doh-ip4-port443-nofilter-ecs-alt
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 149.112.112.12
sdns://AgYAAAAAAAAADjE0OS4xMTIuMTEyLjEyICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczEyLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ

## doh-ip4-port5053-nofilter-ecs-alt
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 149.112.112.12
sdns://AgYAAAAAAAAADjE0OS4xMTIuMTEyLjEyICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczEyLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk

## doh-ip6-port443-nofilter-ecs-pri
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 2620:fe::12
sdns://AgYAAAAAAAAADVsyNjIwOmZlOjoxMl0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTIucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5

## doh-ip6-port5053-nofilter-ecs-pri
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 2620:fe::12
sdns://AgYAAAAAAAAADVsyNjIwOmZlOjoxMl0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTIucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ

## doh-ip6-port443-nofilter-ecs-alt 
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 2620:fe::fe:12
sdns://AgYAAAAAAAAAEFsyNjIwOmZlOjpmZToxMl0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTIucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5

## doh-ip6-port5053-nofilter-ecs-alt 
Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 2620:fe::fe:12
sdns://AgYAAAAAAAAAEFsyNjIwOmZlOjpmZToxMl0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTIucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ

