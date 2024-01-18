-- phpMyAdmin SQL Dump
-- version 5.2.1
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: Jan 18, 2024 at 04:27 AM
-- Server version: 10.4.28-MariaDB
-- PHP Version: 8.2.4

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `payrollsystemdb`
--

-- --------------------------------------------------------

--
-- Table structure for table `tbl_payroll`
--

CREATE TABLE `tbl_payroll` (
  `payroll_id` int(11) NOT NULL,
  `serial_no` int(11) NOT NULL,
  `name` varchar(50) NOT NULL,
  `position` varchar(20) NOT NULL,
  `reg_salary` double NOT NULL,
  `amt_earned` double NOT NULL,
  `pera` double NOT NULL,
  `gross_amt` double NOT NULL,
  `abs_w_o_pay` double NOT NULL,
  `life_insurrance` double NOT NULL,
  `pagibig_cont` double NOT NULL,
  `philhealth` double NOT NULL,
  `withholding_tax` double NOT NULL,
  `deped_prov_loan` double NOT NULL,
  `gsis_gfal` double NOT NULL,
  `gsis_help` double NOT NULL,
  `ucpb_loan` double NOT NULL,
  `eastwest_loan` double NOT NULL,
  `chinabank_loan` double NOT NULL,
  `csb_loan` double NOT NULL,
  `bdo_loan` double NOT NULL,
  `pbb_loan` double NOT NULL,
  `lbp_loan` double NOT NULL,
  `first_total_deduc` double NOT NULL,
  `first_net_amt_due` double NOT NULL,
  `sc_gsis_con_loan` double NOT NULL,
  `sc_gsis_eml` double NOT NULL,
  `sc_gsis_policy` double NOT NULL,
  `sc_gsis_help` double NOT NULL,
  `sc_gsis_gfal` double NOT NULL,
  `sc_gsis_mpl` double NOT NULL,
  `sc_gsis_computer` double NOT NULL,
  `sc_pagibig_mpl` double NOT NULL,
  `sc_pagibig_savings` double NOT NULL,
  `sc_csb_loan` double NOT NULL,
  `sc_ucpb_loan` double NOT NULL,
  `sc_chinabank_loan` double NOT NULL,
  `sc_eastwest_loan` double NOT NULL,
  `sc_bdo_loan` double NOT NULL,
  `sc_lbp_loan` double NOT NULL,
  `sc_total_deduction` double NOT NULL,
  `sc_net_amt_due` double NOT NULL,
  `month` varchar(20) NOT NULL,
  `year` varchar(20) NOT NULL,
  `count_print` int(11) NOT NULL,
  `date_printed` datetime NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Indexes for dumped tables
--

--
-- Indexes for table `tbl_payroll`
--
ALTER TABLE `tbl_payroll`
  ADD PRIMARY KEY (`payroll_id`);

--
-- AUTO_INCREMENT for dumped tables
--

--
-- AUTO_INCREMENT for table `tbl_payroll`
--
ALTER TABLE `tbl_payroll`
  MODIFY `payroll_id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=423;
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
