add_executable(benchmark_tcp_asio_client client.cpp)
target_link_libraries(benchmark_tcp_asio_client Boost::system Boost::thread pthread)

add_executable(benchmark_tcp_asio_server server.cpp)
target_link_libraries(benchmark_tcp_asio_server Boost::system Boost::thread pthread)
