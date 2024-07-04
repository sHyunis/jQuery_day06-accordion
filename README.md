# jQuery Effect method
show() / hide() : display 속성 제어
fadeIn() / fadeOut() / fadeTo(duration, opacity) / fadeToggle()
slideDown() / slideUp() / slideToggle() : height 제어(너비x), 기본값 필수

css({})
->
animate({css 객체}, duration, ease(가속), callback)
// callback이란 : 파라미터로 전달된 함수
// 어떤 특정 작업이 일어나면(event가 발생하면) (뒷)처리 할 일
// css keyframes를 실행하는 것과 같다.
// ease : 'swing'(기본값), 'linear'

# 공통 파라미터
duration
기본값 400, "slow" | "fast", 1000*5(5초 실행)

# 주의
내부적으로 transition, keyframe을 사용하기에
css에 따로 transition을 추가하면 정상작동하지 않는다.

height() / width()