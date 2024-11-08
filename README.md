# hangul-c3d
Emacs용 "참신세벌식D" 내부 한글 입력기
    
## 참신세벌식D Layout
참신세벌식D 자판 정보에 대해서는 다음 링크를 참조해 주세요:
  
[https://doc9107.tistory.com/67](https://doc9107.tistory.com/67)
    
## 사용법 (예)
~/.emacs.d/hangul3/hangul-c3d.el 폴더에 파일을 복사해 두었다고 가정하겠습니다.
그러면, ~/.emacs 파일 또는 ~/.emacs.d/init.el 파일 내에 다음과 같이 적어 두시면 됩니다(만일, doom을 사용하신다면 ~/.doom.d/config.el에 쓰시면 됩니다):
  
(add-to-list 'load-path "~/.emacs.d/hangul3")   
(require 'hangul-c3d)   
(setq default-input-method "korean-hangul-c3d")
  
참고로, emacs내에서 한글 내부 입력기 변환은 Shift+space 또는 Ctrl+backslash를 통해 할 수 있습니다!
