## ಡಾಟ್ ಟೈಮರ್ ಅನ್ನು ರಚಿಸುವುದು

ಟೈಮರ್ ಅನ್ನು ರಚಿಸುವ ಇನ್ನೊಂದು ಮಾರ್ಗವೆಂದರೆ ಪಿಕ್ಸೆಲ್‌ಗಳನ್ನು ಹಸಿರು ಬಣ್ಣದಿಂದ ಕೆಂಪು ಬಣ್ಣಕ್ಕೆ ತಿರುಗಿಸುವುದು.

+ ಡಾಟ್ ಟೈಮರ್ starter trinket: <a href="http://jumpto.cc/dot-timer-go" target="_blank">jumpto.cc/dot-timer-go</a> ತೆರೆಯಿರಿ

+ ವೇರಿಯಬಲ್ `X` ಸೇರಿಸಿ ಪಿಕ್ಸೆಲ್‌ಗಳನ್ನು ಆಫ್ ಮಾಡಲು ಬಳಸಿರಿ - ಅದರ RGB ಮೌಲ್ಯದಲ್ಲಿ ಇದು ಕೆಂಪು, ಹಸಿರು ಅಥವಾ ನೀಲಿ ಬಣ್ಣವನ್ನು ಹೊಂದಿಲ್ಲ:
    
    ![ಸ್ಕ್ರೀನ್‍ಶಾಟ್](images/timer-off.png)

+ ನೀವು ಎಣಿಸಲು ಬಯಸುವ ಸೆಕೆಂಡುಗಳ ಮೌಲ್ಯದೊಂದಿಗೆ `s` ಎಂಬ ವೇರಿಯೇಬಲ್ ಅನ್ನು ಸೇರಿಸಿ.
    
    ![ಸ್ಕ್ರೀನ್‍ಶಾಟ್](images/timer-seconds.png)

+ ನೀವು ಪ್ರದರ್ಶಿಸಲು Sense HATಗೆ 64 (8 × 8) ಬಣ್ಣಗಳ ಪಟ್ಟಿಯನ್ನು ನೀಡಬಹುದು, ಮೇಲಿನ ಎಡಭಾಗದಿಂದ ಪ್ರಾರಂಭಿಸಿ ಮತ್ತು ಒಂದು ಸಮಯದಲ್ಲಿ ಒಂದು ಸಾಲಿನಂತೆ ಕೆಲಸ ಮಾಡಬಹುದು.
    
    ನಾವು ಎಣಿಸಲು ಬಯಸುವ ಪ್ರತಿ ಸೆಕೆಂಡಿಗೆ ಹಸಿರು ಪಿಕ್ಸೆಲ್ ಡಾಟ್ ಅನ್ನು ರಚಿಸಿ ಮತ್ತು ಉಳಿದ 64 ಪಿಕ್ಸೆಲ್‌ಗಳನ್ನು ಆಫ್ ಮಾಡುವ ಮೂಲಕ ಬಣ್ಣಗಳ ಪಟ್ಟಿಯನ್ನು ರಚಿಸೋಣ. `timer` ವೇರಿಯೇಬಲ್ ಪ್ರದರ್ಶಿಸಲು ಬಣ್ಣಗಳ ಪಟ್ಟಿಯನ್ನು ಹೊಂದಿದೆ ಮತ್ತು ಖಾಲಿಯಾಗಿ ಪ್ರಾರಂಭವಾಗುತ್ತದೆ:
    
    ![ಸ್ಕ್ರೀನ್‍ಶಾಟ್](images/timer-setup.png)

+ ಈಗ ಪ್ರತಿ ಸೆಕೆಂಡಿಗೆ ಪಿಕ್ಸೆಲ್ ಕೆಂಪು ಬಣ್ಣಕ್ಕೆ ತಿರುಗಿಸುವ ಮೂಲಕ ಕೌಂಟ್ಡೌನ್ ಅನ್ನು ಚಲಾಯಿಸೋಣ:
    
    ![ಸ್ಕ್ರೀನ್‍ಶಾಟ್](images/timer-turn-red.png)

+ ನೀವು **ಕೊನೆಯಲ್ಲಿ** ಪಿಕ್ಸೆಲ್‌ಗಳನ್ನು ಆನ್ ಮತ್ತು ಆಫ್ ಮಾಡುವ ಮೂಲಕ ಪ್ರದರ್ಶನವನ್ನು ಫ್ಲ್ಯಾಷ್ ಮಾಡಬಹುದು:
    
    ![ಸ್ಕ್ರೀನ್‍ಶಾಟ್](images/timer-flash.png)