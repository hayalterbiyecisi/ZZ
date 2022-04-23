# ZZ
ZZ
 setuptools  ithalat  kurulumundan _

def  parse_requirements ( dosya adı ):
	satırlar  = ( line . strip () açık satır için (  dosya adı ))  
	satırda satır yerine satır için [ satırını  döndürür . _ _ _ _ ile başlar ( "#" )]        

kurulum ( isim = 'DALL-E' ,
        sürüm = '0.1' ,
        açıklama = 'DALL·E için kullanılan ayrık VAE için PyTorch paketi.' ,
        url = 'http://github.com/openai/DALL-E' ,
        yazar = 'Aditya Ramesh' ,
        yazar_email = 'aramesh@openai.com' ,
        lisans = 'BSD' ,
        paketler = [ 'dall_e' ],
        install_requires = parse_requirements ( 'requirements.txt' ),
        zip_safe = Doğru )
