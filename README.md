## JPA (Java Persistence API)
  
- [Configure](#configure)
- [Anotation](#anotation)
- [Proxy](#proxy)
  
## Configure
Set to make up for reference of project
- pom.xml
- persistence.xml  
  
## Anotation
Define to provide table information
- @Entity
- @Table
- @Id
- @GeneratedValue(strategy = GenerationType.IDENTITY)
- @Column(name, nullable, length)
- @Enumerated(EnumType.STRING)
- @Temporal(TemporalType.TIMESTAMP / DATE / TIME)
- @Lob
- @Transient
- @Access(AccessType.FIELD / PROPERTY)
- @ManyToOne
- @OneToOne
- @OneToMany(mappedBy)
- @JoinColumn(name)
- @MappedSuperclass
- @Embedded
- @Embeddable
- @AttributeOverrides
- @ElementCollection
- @CollectionTable
- @PersistenceContext
  
## Proxy  
  
## JPQL (Java Persistence Query Language)
  
## Spring Data JPA
  
  
  
[Ref.] `GitHub mark-down` https://github.com/cheshire137/git-point/blob/master/README.md  
