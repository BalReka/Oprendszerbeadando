r=$RANDOM
R=$((r%=11))

read -R "Gondoltam egy számra 0 és 10 között. Ki találod? SZAM

if [ $R -eq $SZAM ] #egyezés ellenőrzése
    then 
        echo "Gondolat olvasó vagy?"
    else
        if [ $SZAM -gt 10 ] #nagyobb mint 10 vizsgálat
            then 
                echo "Túl lőttél a célon" # ha nagyobb mint 10
            else
                if [ $SZAM -lt 0 ] #minusz szám vizsgálata
                    then 
                        echo "Ne legyél ennyire negatív"
                    else
                        echo "Ezt még gyakorolni kell"
                    fi
            fi        
fi
