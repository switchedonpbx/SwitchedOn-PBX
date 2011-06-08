--
--      _____         _ _       _              _  ____  _   _   _____  ______   __
--     / ____|       (_) |     | |            | |/ __ \| \ | | |  __ \|  _ \ \ / /
--    | (_____      ___| |_ ___| |__   ___  __| | |  | |  \| | | |__) | |_) \ V / 
--     \___ \ \ /\ / / | __/ __| '_ \ / _ \/ _` | |  | | . ` | |  ___/|  _ < > <  
--     ____) \ V  V /| | || (__| | | |  __/ (_| | |__| | |\  | | |    | |_) / . \ 
--    |_____/ \_/\_/ |_|\__\___|_| |_|\___|\__,_|\____/|_| \_| |_|    |____/_/ \_\
-- 
--                               		                        switchedonpbx.org
-- 
--  fop2 - 07/05/2011
-- 
--  SwitchedONPBX-1.0
--  Author: Federico Pereira <info@opentecnologic.com>
--  Coauthor: Ramon Lozano <ramon@solidpc.net>
-- # Copyright 2011 Federico Pereira (LordBaseX)  
--  This script is licensed under GNU GPL version 2.0
--
-- $ID: myextension.sql, v 0.1  2010/05/10 15:57:00 federico Exp $
--
-- freepbx
-- Author: Federico Pereira <fpereira@debpbx.org>
--
-- phpMyAdmin SQL Dump
-- version 2.11.8.1deb5+lenny1
-- http://www.phpmyadmin.net
--
-- Servidor: localhost
-- Tiempo de generación: 20-12-2009 a las 21:03:05
-- Versión del servidor: 5.0.51
-- Versión de PHP: 5.2.6-1+lenny3
--
--
SET SQL_MODE="NO_AUTO_VALUE_ON_ZERO";

-- MODIFYING DEFAULT PASSWORD
-- UPDATE `asterisk_db`.`ampusers` SET `username` =  'FREEPBX_ADMIN',`password_sha1` = 'SHA1_PASS' WHERE CONVERT( `ampusers`.`username` USING utf8 ) = 'admin' LIMIT 1;

-- CONFIGURATION GENERAL SETTINGS
UPDATE `asterisk_db`.`globals` SET `value` =  'trwW' WHERE CONVERT( `globals`.`variable` USING utf8 ) = 'DIAL_OPTIONS' LIMIT 1 ;
UPDATE `asterisk_db`.`globals` SET `value` =  '30' WHERE CONVERT( `globals`.`variable` USING utf8 ) = 'RINGTIMER' LIMIT 1 ;
UPDATE `asterisk_db`.`globals` SET `value` =  'DISABLED' WHERE CONVERT( `globals`.`variable` USING utf8 ) = 'RECORDING_STATE' LIMIT 1 ;
UPDATE `asterisk_db`.`globals` SET `value` =  'ar' WHERE CONVERT( `globals`.`variable` USING utf8 ) = 'TONEZONE' LIMIT 1 ;
UPDATE `asterisk_db`.`globals` SET `value` =  'yes' WHERE CONVERT( `globals`.`variable` USING utf8 ) = 'ALLOW_SIP_ANON' LIMIT 1 ;
INSERT INTO `asterisk_db`.`admin` (`variable` ,`value`) VALUES ('email', 'E_MAIL');

-- FEATURE CODES
UPDATE `asterisk_db`.`featurecodes` SET `enabled` =  '1' WHERE CONVERT( `featurecodes`.`modulename` USING utf8 ) = 'core' AND CONVERT( `featurecodes`.`featurename` USING utf8 ) =  'chanspy' LIMIT 1 


