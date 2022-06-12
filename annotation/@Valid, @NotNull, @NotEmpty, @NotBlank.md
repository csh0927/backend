### @Valid

스프링부트에서 DTO의 필드 조건과, 메시지를 작성해주면 @Valid 어노테이션과 함께 유효성 검사를 할 수 있다.

**유효성 검사**란, 요청한 데이터가 어떤 조건에 충족하는지 확인하는 작업이며, 잘못된 데이터 요청이 들어올 경우 유효성 검사를 통해 처리해주어야 한다. 또한, 유효성 검사는 프론트와 백엔드 모두 다 해주어야 한다. (프론트에서만 유효성 검사를 하는 것은 보안상 위협이된다.)

**DTO**란, 데이터 전달 객체이며, 클라이언트의 요청 데이터가 dto 클래스로 캡슐화 되어서 서버로 전달, 컨트롤러와 서비스 계층 간 데이터를 전달한다.

**@NotNull**
속성값이 Null이 아닌지 확인하는 어노테이션

**@NotEmpty**
속성값이 Null 이거나 비어있지 않은지 확인하는 어노테이션(String, Collection, Map, Array값에만 적용)

**@NotBlank**
텍스트 값에만 적용할 수 있으며 속성이 null 또는 공백이 아닌지 확인하는 어노테이션
