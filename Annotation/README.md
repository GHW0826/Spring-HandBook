## [Annotation](MakeAnnotation/)

### [Spring](Spring/)

- `@Component` : Spring IoC 컨테이너가 클래스를 자동으로 감지해서 Bean으로 등록. 패키지 스캔(Component Scan) 대상에 포함되어 있으면 빈으로 올라옴.

### [Lombok](Lombok/)

- `@Getter/@Setter` : @Getter/@Setter를 붙이면 해당 필드의 getter,setter 메서드를 자동 생성, 클래스에 붙이면 모든 non-static 필드에 getter,setter를 생성.
- `@Data` : 필드 기반으로 `@getter/@setter`, `@toString`, `@equals/@hashCode`, `@RequiredArgsConstructor` 등을 한 번에 생성해주는 어노테이션
- `@ToString` : 클래스의 toString() 메서드를 자동 생성. 설정을 통해 상위 클래스의 출력 포함 여부와 필드 접근 방식을 제어 가능.
- `@NoArgsConstructor` : 파라미터가 없는 기본 생성자를 자동 생성.
- `@RequiredArgsConstructor` : 초기화되지 않은 final 필드와 @NonNull 필드를 위한 필수 파라미터 생성자를 자동 생성.
- `@AllArgsConstructor` : 클래스의 모든 필드에 대해 하나의 파라미터를 갖는 전체 필드 생성자를 자동 생성

### [JPA](JPA/)

- `@Entity` : JPA에서 이 클래스를 테이블과 매핑되는 엔티티로 인식하도록 표시하는 어노테이션
