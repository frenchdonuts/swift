add_swift_unittest(SwiftSyntaxTests
  DeclSyntaxTests.cpp
  ExprSyntaxTests.cpp
  GenericSyntaxTests.cpp
  RawSyntaxTests.cpp
  StmtSyntaxTests.cpp
  SyntaxCollectionTests.cpp
  ThreadSafeCachingTests.cpp
  TriviaTests.cpp
  TypeSyntaxTests.cpp
  UnknownSyntaxTests.cpp
  AbsolutePositionTests.cpp
  )

target_link_libraries(SwiftSyntaxTests
  PRIVATE
  swiftSyntax)
