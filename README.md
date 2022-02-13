# download-in-you-tube
download
 pytube  dan YouTube import 

# Raqamli yoki mahalliy video yoki videoga havola #
havola  =  kiritish ( "Video uchun raqamli yoki havola:" )
yo'l  =  kiritish ( "Raqamli yoki diretório que deseja salvar yoki video:" )
yt  =  YouTube ( havola )

# Videoni batafsil ko'rib chiqing #
chop etish ( "Sarlavha: " , yt . sarlavha )
chop etish ( "Ko'rishlar soni: " , yt . ko'rishlar )
chop etish ( "Tamanho do video: " , yt . length , "segundos" )
chop etish ( "Avaliação do video: " , yt . reyting )

# AQSh katta qaror #
ys  =  yt . oqimlar . eng_yuqori_ravshanlikni olish ()

# Começa yoki video yuklab olish #
chop etish ( "Baixando..." )
ys . Yuklab olish ( yo'l )
chop etish ( "Yuklab olish tugallangan!" )
