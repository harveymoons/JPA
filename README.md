## JPA (Java Persistence API)
  
- [Anotation](#anotation)
- [Configure](#configure)
  
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
  
## Configure
Set to make up for reference of project
- pom.xml
- persistence.xml
  
[Ref.] `GitHub mark-down` https://github.com/cheshire137/git-point/blob/master/README.md   
